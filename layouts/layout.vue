<template>
  <div>
    <!-- <TheHeader /> -->
    <div class="wrapperTopbar"><TopBar /></div>
    <div class="wrapperChildren"><nuxt class="children"/></div>
    <h2>Layout footer</h2>
    <!-- <TheFooter /> -->
  </div>
</template>

<script>
import TopBar from "~/components/topBar/index.vue";

export default {
  components: {
    TopBar
  }
}
</script>

<style>
html {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}
.wrapperTopbar {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: #FFFFFF;
  z-index: 1;
}
.wrapperChildren {
  width: 100%;
  background-color: #bfbfbf;
  padding: 20px;
  padding-top: 86px;
}
.children {
  background-color: #FFFFFF;
  /* margin: 20px; */
  border-radius: 8px;
  max-width: 1224px;
  box-shadow: 0px 0px 10px 10px #00000033;
}
</style>