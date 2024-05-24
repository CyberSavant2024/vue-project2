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

const handleClick = () => {
  // Add functionality for "Buy Now" button
};
</script>

<style scoped>
/* Add styles for the product card here */
.product-card{
  /* Product Card */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 24px 16px;
margin: 0px 6px;
gap: 16px;

width:280px;
min-width: 200px;
height: 432px;

background: #F7F7F7;
border-radius: 9px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 1;}
.image{

  background: #F7F7F7;

}
.product-info{
  /* Apple iPhone 14 Pro Max 128GB Deep Purple (MQ9T3RX/A) */

/* Text+Icon */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: center;
padding: 0px;
gap: 24px;
font-family:  -apple-system,  sans-serif;

width: 236px;
height: 160px;

align-content: center;
align-items: center;
margin: 1% 10%;
/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


}

.but
{
  /* Button */

/* Auto layout */
display: inline-block;


align-items: center;
padding: 1px 6px;
gap: 8px;
font-family:  -apple-system,  sans-serif;
width: 183px;
height: 48px;

/* Main/Black */
background: #000000;
border-radius: 8px;
color: #F7F7F7;
/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;

}
.price{
  /* $1399 */

width: 236px;
height: 24px;

font-family:  -apple-system,  sans-serif;
font-style: normal;
font-weight: 600;
font-size: 24px;
line-height: 24px;
/* identical to box height, or 100% */
text-align: center;
letter-spacing: 0.03em;

/* Main/Black */
color: #000000;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;

}

</style>
