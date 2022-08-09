<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
  <hr />
  <div class="container">
    <button class="btn btn-primary">按鈕</button>
    <p class="fs-3 fs-md-1">
      調整 → _variables.scss Line313 & _utilities.scss Line462
    </p>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
  },
};
</script>
