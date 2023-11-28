<template>
    <div class="items">
<img :src="img" :alt="img" class="item-img">
<p class="item-title">{{ title }}</p>   
  </div>

</template>
<script setup>

const props = defineProps({

  img: {
    type: String,
    required: true,
  },
  title: {
    type: String,
    required: true,
  },
});
</script>
<style>

.items {
    display: flex;
    flex-direction: column;
   align-items: center;
   gap: 18px;
    box-sizing: border-box;
    cursor: pointer;
    
}
.item-img {
width: 199.442px;
height: 199.442px;
flex-shrink: 0;
border-radius: 137.116px; 
/* border: 4px solid #D8EDFD; */
background: lightgray 0px -83.57px / 100% 150.47% no-repeat, rgba(255, 255, 255, 0.17);
}
.item-title {
color: #FFF;
text-align: center;
font-family: Circe;
font-size: 18.282px;
font-style: normal;
font-weight: 400;
line-height: 22.853px; /* 125% */
text-transform: uppercase;
box-sizing: border-box;
width: 145px;
}
</style>