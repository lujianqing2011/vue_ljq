<template>
  <div id="app">
    <transition name="router-fade"  mode="out-in" >
        <router-view></router-view>
    </transition>
  </div>
</template>

<script>

export default {
}
</script>

<style lang="scss">

.router-fade-enter-active,
.router-fade-leave-active 
{
  transition: opacity .2s;
}
.router-fade-enter, 
.router-fade-leave-active 
{
  opacity: 0;
}

@import './style/reset.scss';

</style>
