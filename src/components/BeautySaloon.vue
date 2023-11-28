<template>
    <div class="beauty-saloon">
<h2 class="saloon-title">салоны красоты</h2>
<MenuList />
</div>
</template>
<script>
import MenuList from './MenuList.vue';
</script>
<style>
.beauty-saloon{
    box-sizing: border-box;

}
.saloon-title {
color: #37384C;
/* leading-trim: both;
text-edge: cap; */
font-family: Circe;
font-size: 50px;
font-style: normal;
font-weight: 400;
line-height: 50.3px; /* 100.6% */
text-transform: uppercase;
text-align: center;
margin-top: 120px;
}
</style>