<template>
  <div class="TabbarItems">
    <slot></slot>
    <!-- <slot name="b"></slot> -->
  </div>
</template>

<script>
  export default {
    name:'TabbarItems'
  }
</script>

<style>
  .TabbarItems{
    background-color: blue;
    flex: 1;
    height: 44px;
    line-height: 44px;
    text-align: center;
    font-size: 12px;
  }
  .TabbarItems img{
    width: 22px;
    height: 22px;
  }
</style>