
<script setup>

 const {card} = defineProps({
    
    card:Object,
}

    );
</script>

<template>
    <div class="contt">

    <div class="card">
            <div class="image"><img :src="card.image" alt=""></div>
            <div class="title">{{ card.title }}</div>
        </div>
</div>
</template>
<style scoped>

/* Categories */

/* Auto layout */
.contt{
/* Category Card */
margin: 0 20px;
/* Auto layout */
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 24px 52px;
gap: 8px;




background: #EDEDED;
border-radius: 15px;

/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;



}
.card{

    align-content: center;
    
    align-items: center;
}

.image{
    /* Icon/Phones */

width: 90px;
height: 80px;

margin: 20%  25%  0% 25%;
/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;

}
.title{
    /* Phones */

width: 106px;
height: 24px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 500;
font-size: 25px;
line-height: 24px;
/* identical to box height, or 150% */
text-align: center;

/* Main/Black */
color: #000000;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;

}


</style>