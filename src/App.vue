<template>
  <div id="q-app">
    <error-404></error-404>
    <router-view> </router-view>
  </div>
</template>

<script>
import Error404 from "./pages/Error404.vue";
export default {
  components: { Error404 },
  name: "App",
};
</script>
