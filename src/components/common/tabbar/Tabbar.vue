<template>
  <div class="Tabbar">
    <tabbar-items>
      <img src="@/assets/img/home/home.svg" alt="">
      <!-- <div slot="b">niuwa dadad</div> -->
    </tabbar-items>
  </div>
</template>

<script>
import TabbarItems from "./TabbarItems.vue"
export default {
  name:"Tabbar",
  components:{
    TabbarItems
  }
}
</script>

<style>
  .Tabbar{
    background-color: red;
    display: flex;
    width: 100%;
    position: fixed;
    bottom: 0;
    right: 0;
    left: 0;
  }
</style>