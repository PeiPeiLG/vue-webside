<template>
  <section class="about mt-59 mt-md-88 mt-lg-97 text-dark">
    <div class="container">

      <section class="pt-3 pt-md-5">
        <!--照片名字-->
        <div class="row justify-content-center align-items-center">
          <div class="col-12 col-md-3 text-center">
            <img class="photo-img rounded-circle" alt="photo" src="../assets/photo.jpg">
          </div>
          <div class="col-12 col-md-5 text-center text-md-left">
            <div class="row">
              <div class="col-12">
                <h2 class="mb-0 mt-2 fz-3">羅恩培</h2>
                <p class="fz-6 mb-2">Lo-En-Pei</p>
              </div>
              <div class="col-12">
                <p class="fz-6 fz-md-5 text-info">"程式是種樂趣，是訴說想像的語言無須畏懼"</p>
              </div>
            </div> 
          </div>
        </div>

        <!--簡短介紹-->
        <p class="text-justify text-indent fz-6 fz-md-5 mt-md-3">
          畢業於資訊工程學系，第一份工作是使用Unity開發AR/VR軟體並且上架APP，偶然接觸網路上網頁教學課程對寫網頁產生很大的興趣，並且進入這行工作了一年多，原以為網頁程式已經是資訊這領域相對單純的東西了，沒想到踏進來才知道這裡宛如一片大海，學得越多感覺不會的就更多，未來我將成為人人都覺得厲害的前端甚至是全端工程師。
        </p>
      </section>

      <!--技能-->
      <section class="my-3">      
        <h2 class="font-weight-bold fz-5 fz-md-4">#技能</h2>
        <div class="row">
          <!--html-->
          <div class="col-md-6 mt-0 mt-md-3">
            <h5 class="card-title fz-6"><i class="fab fa-html5 mr-1"></i>Html5</h5>
            <div class="card">
              <div class="card-body">
                <ul class="list-group list-group-flush list-group-style fz-6">
                  <li class="list-group-item">運用Emmet方式加速Html撰寫速度</li>
                  <li class="list-group-item">用正確的標籤做正確的事，加強Html語意化有利於提升SEO</li>
                  <li class="list-group-item">控制網頁記憶體提高網頁渲染速度</li>
                </ul>
              </div>
            </div>
          </div>
          <!--css-->
          <div class="col-md-6 mt-3">
            <h5 class="card-title fz-6"><i class="fab fa-css3-alt mr-1"></i>Css3</h5>
            <div class="card">
              <div class="card-body">
                <ul class="list-group list-group-flush list-group-style fz-6">
                  <li class="list-group-item">使用OOCSS、SMACSS、BEM來模組化架構，增加CSS彈性</li>
                  <li class="list-group-item">使用Sass的Scss寫法來做CSS分類</li>
                  <li class="list-group-item">活用Bootstrap + 手刻Scss加速開發效率</li>
                </ul>
              </div>
            </div>
          </div>
          <!--JavaScript-->
          <div class="col-md-12 mt-3">
            <h5 class="card-title fz-6"><i class="fab fa-js-square mr-1"></i>JavaScript</h5>
            <div class="card">
              <div class="card-body">
                <div class="row">
                  <div class="col-md-6">
                    <ul class="list-group list-group-flush list-group-style fz-6">
                      <li class="list-group-item">善用ES6版本增加程式效能並且用Babel編譯</li>
                      <li class="list-group-item">AJAX JSON 非同步資料傳遞</li>
                    </ul>
                  </div>
                  <div class="col-md-6">
                    <ul class="list-group list-group-flush list-group-style fz-6">
                      <li class="list-group-item">善用 jQuery Plugin 整合第三方插件動畫效果</li>
                    </ul>
                  </div>
                </div>
          
                <!--Vue-->
                <h6 class="card-subtitle mt-3 mb-1 text-secondary"><i class="fab fa-vuejs mr-1"></i>Vue.js</h6>
                <div class="row">
                  <div class="col-md-6">
                    <ul class="list-group list-group-flush list-group-style fz-6">
                      <li class="list-group-item">運用基本模板控制DOM元素跟內容</li>
                      <li class="list-group-item">使用x-template模組化元件，並且透過prop跟emit內外傳遞資料</li>
                    </ul>
                  </div>
                  <div class="col-md-6">
                    <ul class="list-group list-group-flush list-group-style fz-6">
                      <li class="list-group-item">啟用Vue Cli並且引用帶入專屬API</li>
                      <li class="list-group-item">使用Vue Cli3 + Vue Router 整合製作SPA網頁</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
          <!--設計-->
          <div class="col-md-6 mt-3">
            <h5 class="card-title fz-6"><i class="fas fa-paint-brush mr-1"></i></i>設計</h5>
            <div class="card">
              <div class="card-body">
                <ul class="list-group list-group-flush list-group-style fz-6">
                  <li class="list-group-item">Adobe Photoshop 基本製圖</li>
                  <li class="list-group-item">Adobe Illustrator 基本製圖</li>
                  <li class="list-group-item">Adobe Premiere 基本影片剪輯</li>
                  <li class="list-group-item">Adobe After Effects 基本動畫特效</li>
                </ul>
              </div>
            </div>
          </div>
          <!--其他-->
          <div class="col-md-6 mt-3">
            <h5 class="card-title fz-6">其他</h5>
            <div class="card">
              <div class="card-body">
                <ul class="list-group list-group-flush list-group-style fz-6">
                  <li class="list-group-item">npm 做套件管理工具</li>
                  <li class="list-group-item">Gulp 做專案管理工具</li>
                  <li class="list-group-item">Git 做程式版本控制</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--工作經驗-->
      <section class="my-3">
        <h2 class="font-weight-bold fz-5 fz-md-4">#工作經驗</h2>
        <ul class="list-style-none border-left border-secondary pl-3 ml-3">
          <li class="point mt-3">
            遠颺科技股份有限公司 <br>[軟體工程師]<span class="ml-4 fz-7">2017.9~ 2018.3</span>
            <ul class="list-style-square">
              <li class="mt-2">使用Unity開發AR/VR互動遊戲</li>
              <li class="mt-2">幫助iOS跟Android軟體上架</li>
              <li class="mt-2">研究Arduin結合Unity</li>
            </ul>
          </li>
          <li class="point mt-3">
            德榕企業有限公司 <br>[前端工程師]<span class="ml-4 fz-7">2019.12~ 2021.1</span>
            <ul class="list-style-square">
              <li class="mt-2">獨立完成大型官網前端開發</li>
              <li class="mt-2">獨力完成一頁式RWD前端網頁開發</li>
              <li class="mt-2">獨力完成一頁式活動網頁開發</li>
              <li class="mt-2">獨力完成無障礙網頁製作</li>
              <li class="mt-2">大型官網定期維護修改</li>
              <li class="mt-2">小型網頁介面設計</li>
              <li class="mt-2">公司官網影片剪輯</li>
            </ul>
          </li>
        </ul>
      </section>

      <!--短期目標-->
      <section class="my-3">
        <h2 class="font-weight-bold fz-5 fz-md-4">#短期目標</h2>
        <p class="text-justify fz-6 fz-md-5 mt-md-3 pl-4">
          1.將一種JS框架靈活運用在各種專案上。<br>
          2.增加自己的英文能力。<br>
          3.持續加強自己的英文打字速度    
        </p>
      </section>

       <!--長期目標-->
      <section class="my-3">
        <h2 class="font-weight-bold fz-5 fz-md-4">#長期目標</h2>
        <p class="text-justify fz-6 fz-md-5 mt-md-3 pl-4">
            將前端技術到達專業水準後，慢慢往全端方展。
        </p>
      </section>    


    </div>
    
  </section>
</template>

<style>
  .photo-img{
    width: 150px;
  }
  @media (min-width: 992px){
    .photo-img{
      width: 200px;
    }
  }
</style>

<script>

</script>