<template>
  <section class="works mt-59 mt-md-88 mt-lg-97 py-4">
    <div class="container">
      <!--Vue-cli3(SPA)-->
      <div>
        <h2 class="font-weight-bold fz-5 fz-md-4 text-dark">Vue-cli3(SPA)</h2>
        <ul class="row list-style-none m-0 p-0">
          <li class="col-md-6 col-lg-4 py-2" >
            <div @click="modelContent('vueCli',0)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img :src="require('../assets/works/vue-webside.jpg')" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">個人網站</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> vue-cli3</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> vue-router</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> npm</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> vue-typed-js</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> bootstrap</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <!--<li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('vueCli',1)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/test.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">這是標題喔</template>
                <template slot="cardText">這是介紹</template>
              </HoverCard>
            </div>
          </li>-->
        </ul>
      </div>
      <!--大型官網-->
      <div class="mt-3">
        <h2 class="font-weight-bold fz-5 fz-md-4 text-dark">大型官網</h2>
        <ul class="row list-style-none m-0 p-0">
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('largeSite',0)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/rmk.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">RMK台灣官方網站</template>
                <template slot="cardText">
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> RWD</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> swiper.js</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> iframe</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('largeSite',1)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/deerdogs.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">deerdogs官方網站</template>
                <template slot="cardText">
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> RWD</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> swiper.js</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> jQuery TWzipcode</span>              
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('largeSite',2)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/hiq.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">Hi-Q中華海洋官方網站</template>
                <template slot="cardText">
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> RWD</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> swiper.js</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> fancybox</span>              
                </template>
              </HoverCard>
            </div>
          </li>
        </ul>
      </div>
      <!--簡易型官網-->
      <div class="mt-3">
        <h2 class="font-weight-bold fz-5 fz-md-4 text-dark">簡易型官網</h2>
        <ul class="row list-style-none m-0 p-0">
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('smallSite',0)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/lulua.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">鹿鹿A官方網站</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> viewport750</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> fancybox</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('smallSite',1)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/rice.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">池田好米</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> loading動畫</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> OOCSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> SMACSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> BEM</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> animation</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> swiper.js</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> AOS</span>
                </template>
              </HoverCard>
            </div>
          </li>
        </ul>
      </div>
      <!--一頁式RWD活動頁-->
      <div class="mt-3">
        <h2 class="font-weight-bold fz-5 fz-md-4 text-dark">一頁式RWD活動頁</h2>
        <ul class="row list-style-none m-0 p-0">
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('rwdActivity',0)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/suqqu.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">SUQQU 聖誕活動</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> RWD</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> OOCSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> SMACSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> BEM</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> iframe</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('rwdActivity',1)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/light_up.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">台電 | 風傳媒</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> RWD</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> OOCSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> SMACSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> BEM</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> animation</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('rwdActivity',2)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/laprairie.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">LA PRAIRIE活動網站</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> RWD</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> SCSS</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> form表單</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> 影片自動撥放</span>
                </template>
              </HoverCard>
            </div>
          </li>          
        </ul>
      </div>
      <!--一頁式活動頁-->
      <div class="mt-3">
        <h2 class="font-weight-bold fz-5 fz-md-4 text-dark">一頁式活動頁</h2>
        <ul class="row list-style-none m-0 p-0">
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('activity',0)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/darphin.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">DARPHIN小官網與活動網站群</template>
                <template slot="cardText">
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> viewport750</span>
                    <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> AOS</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('activity',1)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/apivita.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">APIVITA活動網站群</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> viewport750</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> AOS</span>
                </template>
              </HoverCard>
            </div>
          </li>
          <li class="col-md-6 col-lg-4 py-2">
            <div @click="modelContent('activity',2)" data-toggle="modal" data-target=".bd-example-modal-xl">
              <HoverCard>
                <img src="../assets/works/sisley.jpg" alt="" slot="cardImg" class="card-img">
                <template slot="cardTitle">SISLEY 活動網站群</template>
                <template slot="cardText">
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> 類RWD</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> form表單</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> 影片自動撥放</span>
                  <span class="badge badge-primary m-1"><i class="fas fa-hashtag"></i> iframe</span>
                </template>
              </HoverCard>
            </div>
          </li>          
        </ul>
      </div>      
    </div>

<!-- Modal -->
<div class="modal fade bd-example-modal-xl" tabindex="-1" role="dialog" aria-labelledby="myExtraLargeModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-xl">
    <div class="modal-content border-0">
      <div class="modal-header overflow-hidden mh-450 p-0 ">
        <img :src="require('../assets/works/'+ this.imgName +'.jpg')" class="card-img-top" alt="...">
      </div>
      <div class="modal-body">
        <div class="card border-0">
          <div class="card-body">
            <h5 class="card-title font-weight-bold fz-5 fz-md-4">{{ this.title }}<a :href="this.link" target="_blank" rel="noreferrer noopener" class="text-info ml-2"><i class="fas fa-link"></i></a></h5>
            <p class="card-text  fz-6 fz-md-5">{{ this.introduction }}</p>
            <p class="card-text  fz-6 fz-md-5"> <span class="font-weight-bold">負責內容:</span> {{ this.responsible }}</p>
            <div>
              <span class="badge badge-primary m-1" v-for="(item , key) in this.tag" :key="key"><i class="fas fa-hashtag ml-1"></i>{{ item }}</span>
            </div>
          </div>
        </div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>   
    
   
  </section>
</template>


<script>
  import HoverCard from '../components/HoverCard.vue';
  export default {
    
    name: 'Works',
    data(){
      return{
        workData: {},
        tagArray:[],
        imgName: 'test',
        link:'',
        introduction: '',
        responsible: '',
        tag:[],
        title: '',
      }       
    },
    created() {
      this.$http.get('/vue-webside/dist/worksData.json').then(res => {
      this.workData = res.body;
      })
    },
    methods: {
      modelContent(types,n){
        switch(types){
          case 'vueCli':
          this.title = this.workData.vueCli[n].title;
          this.link = this.workData.vueCli[n].link;
          this.imgName = this.workData.vueCli[n].imgName;
          this.introduction = this.workData.vueCli[n].introduction;
          this.responsible = this.workData.vueCli[n].responsible;
          this.tag = this.workData.vueCli[n].tag;
          break;
          case 'largeSite':
          this.title = this.workData.largeSite[n].title;
          this.link = this.workData.largeSite[n].link;
          this.imgName = this.workData.largeSite[n].imgName;
          this.introduction = this.workData.largeSite[n].introduction;
          this.responsible = this.workData.largeSite[n].responsible;
          this.tag = this.workData.largeSite[n].tag;
          break;
          case 'smallSite':
          this.title = this.workData.smallSite[n].title;
          this.link = this.workData.smallSite[n].link;
          this.imgName = this.workData.smallSite[n].imgName;
          this.introduction = this.workData.smallSite[n].introduction;
          this.responsible = this.workData.smallSite[n].responsible;
          this.tag = this.workData.smallSite[n].tag;
          break;
          case 'rwdActivity':
          this.title = this.workData.rwdActivity[n].title;
          this.link = this.workData.rwdActivity[n].link;
          this.imgName = this.workData.rwdActivity[n].imgName;
          this.introduction = this.workData.rwdActivity[n].introduction;
          this.responsible = this.workData.rwdActivity[n].responsible;
          this.tag = this.workData.rwdActivity[n].tag;
          break;
          case 'activity':
          this.title = this.workData.activity[n].title;
          this.link = this.workData.activity[n].link;
          this.imgName = this.workData.activity[n].imgName;
          this.introduction = this.workData.activity[n].introduction;
          this.responsible = this.workData.activity[n].responsible;
          this.tag = this.workData.activity[n].tag;
          break;
        }
      },
    },
    components: {
      HoverCard,
    },
  };
</script>
