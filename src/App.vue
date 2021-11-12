<template>
  <NavMain />
  <router-view/>
</template>

<script>
import NavMain from "@/components/NavMain.vue"
export default {
  components: {
    NavMain
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
