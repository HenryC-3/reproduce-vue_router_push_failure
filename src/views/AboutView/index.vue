<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="about">
    <router-link to="/about/child">go to "/about/child"</router-link>
    <router-view></router-view>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
