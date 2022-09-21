<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="about">
    <h1>This is an Child page</h1>
    <button @click="go">test</button>
  </div>
</template>

<script setup>
import { useRouter } from "vue-router";
// import router from "../../router";

const go = () => {
  const router = useRouter();
  router.push("/");
  // router.push("/");
};
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
