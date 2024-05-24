<script setup   ></script>
 
 
 <template>
 <div class="banner">

    <div class="content">
        <div class="pro"> Pro beyond</div>
          <div class="iphone">IPHONE 14 <b>PRO</b></div>
            <div class="creat"> created to change everything for better for everyone </div>
        <button class="but" type="text">shop now</button>
    </div>
    <div class="img"><img src="/assets/IphoneImage.png" alt=""></div>

 </div>
   

    
 </template>


<style scoped>
/* Banner */

/* Auto layout */
.banner{
    
display: flex;
flex-direction: row;
flex-wrap: wrap;
justify-content: space-between;
align-items: center;
align-content: flex-start;
padding: 0px 160px;
gap: 24px 213px;

width: 100%;
height: 632px;

background: linear-gradient(90.7deg, #211C24 0.64%, #211C24 101%);

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;

}
.content{
    /* Content */
color:  #FFFFFF;

/* Auto layout */
/* Content */

/* Auto layout */
/* Titles */

/* Auto layout */




}

.pro
{
/* Pro.Beyond. */
padding: 14px;
width: 714px;
height: 32px;

font-family: 'Figtree';
font-style: normal;
font-weight: 600;
font-size: 25px;
line-height: 32px;
/* identical to box height, or 128% */

color: #FFFFFF;

opacity: 0.4;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;

}
.iphone{
    /* IPhone 14 Pro */
padding: 14px;
width: 1000px;
height: 72px;

font-family: -apple-system, BlinkMacSystemFont, sans-serif;
font-style: normal;
font-weight: 200;
font-size: 96px;
line-height: 72px;
/* identical to box height, or 75% */
letter-spacing: -0.01em;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;

}
.creat{
    /* Created to change everything for the better. For everyone */
padding: 14px;
width: 714px;
height: 24px;

font-family: 'SF Pro Display';
font-style: normal;
font-weight: 500;
font-size: 18px;
line-height: 24px;
/* identical to box height, or 133% */

color: #919191;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;

}
.but{
    /* Label */

width: 175px;
height: 50px;

font-family: -apple-system, BlinkMacSystemFont, sans-serif;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 24px;
/* identical to box height, or 150% */
text-align: center;
border-color: #FFFFFF;
border-radius: 8px;

/* Main/White */
color: #FFFFFF;

background:  linear-gradient(90.7deg, #211C24 0.64%, #211C24 101%);
/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;

    
}
.img{
    position: absolute;
    right:40em;

}
.content{
    margin-top:5%
}

</style>