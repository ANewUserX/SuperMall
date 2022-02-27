<template>
  <div id="TabbarItems">
    <div class="item-ico"><slot name="ico"></slot></div>
    <div class="item-txt"><slot name="txt"></slot></div>
  </div>
</template>

<script>
  export default {
    name:'TabbarItems'
  }
</script>

<style>
  #TabbarItems{
    flex: 1;
    height: 44px;
    line-height: 44px;
    text-align: center;
  } 
</style>