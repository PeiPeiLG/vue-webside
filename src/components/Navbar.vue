<template>
  <nav id="nav" class="navbar navbar-expand-lg navbar-light bg-primary px-lg-5 py-lg-3 fixed-top border-bottom border-third" ref="navBox">
      <div class="d-flex justify-content-between align-items-center w-100 z-index-2">
        <router-link class="navbar-brand p-0" to="/"><img @click="navberClose" class="border border-third rounded-circle logo-img" width="56" alt="web logo" src="../assets/peiLogo.png"></router-link>
        <button class="navbar-toggler border-0" type="button" >
          <div class="pointer d-inline-block js-toggle" :class="{ 'change' : isTransform }" @click="isTransform = !isTransform">
            <div class="bar1"></div>
            <div class="bar2"></div>
            <div class="bar3"></div>
          </div>
        </button>
      </div>
      <transition name="fade">
        <div v-if="isTransform" class="navbar-collapse navber-fixed-fluid " id="navbarNav">
          <ul class="navbar-nav ml-lg-auto">
            <li class="nav-item" @click="navberClose">
              <router-link class="nav-link font-weight-bold fz-4 fz-lg-6 p-3" to="/about">About</router-link>
            </li>
            <li class="nav-item" @click="navberClose">
              <router-link class="nav-link font-weight-bold fz-4 fz-lg-6 p-3" to="/works">Works</router-link>
            </li>
            <li class="nav-item" @click="navberClose">
              <router-link class="nav-link font-weight-bold fz-4 fz-lg-6 p-3" to="/blog">Blog</router-link>
            </li>
            <li class="nav-item" @click="navberClose">
              <router-link class="nav-link font-weight-bold fz-4 fz-lg-6 p-3" to="/contact">Contact</router-link>
            </li>
          </ul>
        </div>
      </transition>
      
    </nav>
</template>

<style lang="scss" scoped>
  .bar1, .bar2, .bar3 {
    width: 25px;
    height: 3px;
    background-color: #34EA7E;
    margin: 4px 0;
    transition: 0.4s;
  }
  @media (min-width: 768px) {
      .bar1, .bar2, .bar3 {
        width: 35px;
        height: 5px;
        margin: 6px 0;
    }
  }
  .change{
    .bar1 {
      -webkit-transform: rotate(-50deg) translate(-9px, 6px);
      transform: rotate(-50deg) translate(-9px, 6px);
    }
    .bar3 {
        -webkit-transform: rotate(45deg) translate(-2px, -2px);
        transform: rotate(45deg) translate(-2px, -2px);
      }
    .bar2 {opacity: 0;}
    
  }
  @media (min-width: 768px) {
    .change{
      .bar3 {
        -webkit-transform: rotate(45deg) translate(-8px, -8px);
        transform: rotate(45deg) translate(-8px, -8px);
      }
    }
  }

.logo-img{
  width: 35px;
  margin: .25rem .75rem;
}
@media (min-width: 768px) {
  .logo-img{
    width:56px;
  }
}
</style>

<script>
  export default {
    name: 'Navber',
    data (){
      return{
        //控制navber開關
        isTransform : false,
        height:0,
      }
    },
    created() {
      //判斷目前寬度
      let w = window.innerWidth;
      //若是PC則打開navbar
      if( w >=991.98){
        this.isTransform = true;
        console.log('這螢幕應該是pc' , this.isTransform);
      }
      
    },
    methods: {
      navberClose(){
        let w = window.innerWidth;
       
        if( w < 991.98){
          this.isTransform = false;
        }else{
          console.log('這是pc所以navber不會關喔!');
        }
      },
    },
    
  }
</script>
