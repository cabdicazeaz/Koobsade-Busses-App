
<script setup lang="ts">
import { RouterView,RouterLink} from 'vue-router';
import Nav from "./components/Nav.vue";
import Home from './components/pages/Home.vue';


</script>




<template>
<Nav /> 
<Home/>
  <RouterView />
</template>



