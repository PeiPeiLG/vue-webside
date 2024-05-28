<template>
  <section class="home mt-59 mt-md-88 mt-lg-97">
    <div class="container-fluid">
      <div class="master position-relative mx-auto my-0 py-3">
        <img src="../assets/master-bg.png" alt="主視覺背景">
        <div class="position-absolute top-0 left-0 w-100 h-100 d-flex justify-content-center align-items-center">
           <vue-typed-js :strings="['程式是種樂趣<br>是訴說想像的語言無須畏懼']" :startDelay="300" :contentType="'html'" :showCursor="false" :typeSpeed="80">
            <p class="typing mb-0 text-center fz-7 fz-md-4 font-weight-bold text-dark"></p>
          </vue-typed-js>
        </div>
      </div>
    </div>
    
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
}
</script>

<style lang="scss" scoped>
  .master{
    max-width: 800px;
    img{width: 100%}
  }
</style>
<script>
export default {
  data(){
    return{
      masterText: `程式是種樂趣<br>是訴說想像的語言無須畏懼|`,
    }
  },
}

</script>
