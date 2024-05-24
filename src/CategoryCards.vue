 <script setup >
 import {cards} from './cards'
 import Category from './Category.vue';
 
 
 


</script>

<template>
<div class="cat">
   <div class="line">
   <h2 class="gat"> browse by Categories   
</h2><div class="but">
<button class="left">l</button>
   <button class="right">r</button>
</div>
</div>
<div class="f">
 
   <Category v-for ="car in cards" :card="car" />
</div>

</div>

</template>
<style scoped>

.cat{
   position: relative;
   width: 100%;
   
   align-content: center;
align-items: center;
align-self: center;


}

.f{

display: flex;
align-content: center;
align-items: center;
align-self: center;
margin:0% 10% 0% ;
height: 150px;




}
.gat{
   /* Browse By Category */

margin: 3% 11%;

height: 32px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 500;
font-size: 34px;
line-height: 32px;
/* identical to box height, or 133% */
letter-spacing: 0.01em;

/* Main/Black */
color: #000000;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;




}
.line{
   display:flex
}
.but{
   display: flex;
   margin-left:62%;
   height: 34px;
   margin-top:3%;
   
}
.left{
   width:50px;
   background-color: white;
   border: none;
}
.right{
   width:50px;
   background-color: white;
   border: none;

}
</style>