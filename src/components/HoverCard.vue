<template>
  <div class="card text-white border-primary" @mouseenter="hover = true" @mouseleave="hover = false">
    <slot name="cardImg"></slot>
    <transition name="fade">
      <div class="card-img-overlay backdrop-filter bg-dark-opacity pointer" v-show="hover">
        <h3 class="card-title font-weight-bold fz-6 fz-md-5 ">
          <slot name="cardTitle">標題</slot>
        </h3>
        <p class="card-text fz-7 fz-md-6">
          <slot name="cardText">內文或標籤</slot>
        </p>
      </div>
    </transition>
  </div>
</template>

<script>
export default {
  data (){
    return {
      hover: false,
    }   
  },
}
</script>