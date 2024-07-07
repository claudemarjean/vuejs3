<template>
  <HelloWorld :sub-title="subTitle"/>
  <br>
  <input type="text" v-model="subTitle">
</template>

<script setup>

import HelloWorld from "@/components/HelloWorld.vue";
import { ref } from 'vue';


const subTitle  = ref("Lorum Ipsum");

</script>

<style scoped>

</style>
