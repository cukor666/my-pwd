<template>
  <div class="container">
    <h1>{{title}}</h1>
  </div>
</template>

<script setup>
import {ref} from "vue";

const title = ref('Welcome to my app')
</script>