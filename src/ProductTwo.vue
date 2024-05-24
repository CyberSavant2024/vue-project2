<script setup>


import ProductCard from './ProductCard.vue';


   const      cards=[
    {
        image:"/assets/image/h.png",
        name:"AirPods Max Silver",
        price:"435",



    },
    {
        image:"/assets/image/ph1.png",
        name:"Apple iPhone 14 Pro 1TB Gold (MQ2V3)",
        price:"1445",
        


    },  {
        image:"/assets/image/ph2.png",
        name:"Apple iPhone 14 Pro 512GB Gold (MQ233)",
        price:"1234",
        


    },  
    {
        image:"/assets/image/watch.png",
        name:"Apple Watch Series 9 GPS 41mm Starlight Aluminium Case",
        price:"345",
        


    },
];

</script>

<template>


<div class="banner">
    <div class="text">Discounts up to -50%</div>
</div>
    <div class="producdt">

    <ProductCard v-for="pa in cards " :product="pa" />

</div>
</template>

<style scoped>
.producdt{

    display: flex;
    width:80%;
    align-items: center;
    align-content: center;
    
   
    padding: 1% 3%;
    
}
.text{
    margin :1% 3%;
    font-size: 28px;
    font-family:  -apple-system,  sans-serif;


    
}

</style>