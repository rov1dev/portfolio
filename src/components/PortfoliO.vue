<template>
  <section id="blog">
    <h2 class="port-title">Portfolio</h2>
    <div class="port-container">
        <div v-for="(data,ind) in datas" :key="ind">
        
        </div>
    </div>
  </section>
</template>

<script setup>
import {ref} from 'vue';

const datas = ref([
    {
        link:'https://vanilla-js-store.netlify.app/',
        name:"Comfy store"
    },
    {
        link:'https://vanilla-js-basic-project-8-menu.netlify.app/',
        name:"Our menu"
    },
    {
        link:'https://vannilla-js-basic-project-20-filters.netlify.app/',
        name:"Filters"
    },
    {
        link:'https://vannilla-js-basic-project-22-products.netlify.app/',
        name:"Products"
    }
])
</script>

<style lang="scss" scoped></style>
