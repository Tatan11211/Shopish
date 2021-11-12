<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <title>Este es un titulo</title>
    <HelloWorld msg="Bienvenido a amigos de la pesca"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorld,
  },
});
</script>