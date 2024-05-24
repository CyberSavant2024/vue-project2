<script setup >
import { products } from './products';
import ProductCard from './ProductCard.vue';
</script>

<template>

  <div class="card">
    <div class="title">

       <div class="new">New arrival</div>
       <div class="sec"> Bestseller</div>
       <div class="thr"> Featured Products</div>
    </div>
    <div class="product-catalog">
    <ProductCard v-for="produc in products"  :product="produc"  />
  </div>

</div>
</template>

<style scoped >

.product-catalog{
  
    display: flex;
    width:60%;
    align-items: center;
    align-content: center;
   
    padding: 1% 3%;
}
.title{
  display :flex;
  padding: 2% 3% 1%;
  

}
.thr{
  /* Featured Products */


height: 32px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 500;
font-size: 28px;
line-height: 32px;
/* identical to box height, or 178% */

color: #8B8B8B;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;

}
.sec{


  /* Featured Products */

width: 143px;
height: 32px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 500;
font-size: 28px;
line-height: 32px;
/* identical to box height, or 178% */

color: #8B8B8B;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;

}
.new{
  /* Selected */

/* Auto layout */
display: flex;
flex-direction: column;
justify-content: center;
align-items: flex-start;
padding: 0px;
font-size: 28px;

height: 32px;
margin-right:40px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;

}
.thr:hover{
  color:black;
  
}

</style>
