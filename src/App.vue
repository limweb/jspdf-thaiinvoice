<template>
  <div class="bg-green-500 text-red" style="background-color: coral">
    Header
  </div>
  <Invoice />
  <div class="bg-red-200">Footer</div>
</template>

<script>
import Invoice from "./components/Invoice.vue";
export default {
  name: "App",
  components: {
    Invoice,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
