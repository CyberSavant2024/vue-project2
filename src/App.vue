
<script setup >
import { defineProps,ref } from 'vue';
import Banner from './Banner.vue';


import { products } from './products';
import ProductCard from './ProductCard.vue';
import Header from './Header.vue';
import Footer from './Footer.vue'
import ProductGrid from './ProductGrid.vue';
const imageUrl = ref("file:///C:/Users/naiti/Downloads/Iphone%20Image.svg")
import BannerTwo from './BannerTwo.vue';
import CategoryCards from './CategoryCards.vue';
import ProductTwo from './ProductTwo.vue';
</script>

<template>
<Header/>
<Banner/>
<CategoryCards/>


<ProductGrid/>

<BannerTwo/>



<ProductTwo/>

<Footer/>
</template>



 <style scoped>

</style>