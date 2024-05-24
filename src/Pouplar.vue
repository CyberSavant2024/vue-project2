<template>

    <div>
    <div class="product-card">
      <div class="image">
      <img :src="product.image" alt="Product Image">
    </div>
      <div class="product-info">
        
        <div><h2>{{ product.name }}</h2></div>
        
        <div class="price">$ {{ product.price }}</div>
        
        
        
      
      </div>
      <div>
      <button class="but">Buy Now</button>
    </div>
      
  
      
    </div>
    
    
  </div>
  
  </template>
  
<script setup>
const { product } = defineProps({
  product: Object, // Define prop type
}); // Import product prop
