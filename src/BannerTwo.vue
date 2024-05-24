<script setup >

</script>


<template>

   


 <div class="banner">
    <div class="firstimg">
        <img src="/assets/image6.png" alt="">
    </div>
    

    <div class="thirdimg"><img src="/assets/jbl_jr_310bt_blue 1.png" alt=""></div>
    <div class="secondimg"><img src="/assets/image18.png" alt=""></div>
 <div class="conte">
    <div class="text">
    <div class="title">
        Big Summer <b>  Sale </b>
    </div>

    <div class="under">
        Commodo fames vitae vitae leo mauris in. Eu consequat.
        </div>
            <div class="buttom">
        <button class="but">shop now</button>
    </div>
    </div>


 </div>  
 
 

 <div class="forth">
    <img src="/assets/image45.png" alt="">
 </div>
 <div class="fifth"><img src="/assets/image7.png" alt=""></div>

 </div>
    



</template>


<style scoped>
.banner{
    /* Banner 2 */

/* Auto layout */

display: flex;
position: relative;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 110%;
height: 448px;

background: linear-gradient(100.23deg, #2E2E2E 42.36%, #000000 98.65%);

/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;



}

.title{
    /* Big Summer Sale */

width: 491px;
height: 72px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 200;
font-size: 72px;
line-height: 72px;
/* identical to box height, or 100% */
text-align: center;
letter-spacing: -0.01em;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;

}
.under{
    /* Commodo fames vitae vitae leo mauris in. Eu consequat. */

width: 491px;
height: 32px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 32px;
/* identical to box height, or 200% */
text-align: center;

color: #787878;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;

}
.but{
    /* Button */

box-sizing: border-box;

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 16px 56px;
gap: 8px;
background: linear-gradient(100.23deg, #2E2E2E 42.36%, #2f2929 98.65%);

width: 184px;
height: 56px;

/* Main/White */
border: 1px solid #FFFFFF;
border-radius: 6px;
color:#FFFFFF;
/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;

}
.firstimg{
    

/* image 6 */
float: left;
position:absolute;


/* image 6 */


left: 8%;


top:0%;



/* Inside auto layout */

}
.title{
    display:inline
}

.but{
    align-content: center;
    align-items: center;
    
}
.buttom{
    align-content: center;
    align-items: center;
    margin: auto;
    padding-left:29% ;

    margin-top: 10%;
}

.secondimg{
   
    position: absolute;
    left: 2%;
    top:5%;
    



}
.thirdimg{

    position:absolute;
    left:0%;
    bottom:0%;

}
.forth{
    position:absolute;
    right: 0%;
    top:3%;


}
.fifth{
    position:absolute;

    right:0%;
    
  bottom:0%

}

</style>