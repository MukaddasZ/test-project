<template>
  <div class="banner">
    <img src="@/assets/bubble.svg" alt="bubble" class="banner-bubble" />

    <div class="banner-content">
  <div class="banner-logo">Fancy's</div>
  <div class="banner-description1">cкоро открытие спа-салона osha в астане</div>
  <div class="banner-description2">ВЫ СМОЖЕТЕ НАСЛАДИТЬСЯ ТАКИМИ УСЛУГАМИ КАК ТУРЕЦКИЙ ХАМАМ, ПИЛИНГ, МАССАЖ И МНОГО ДРУГОЕ</div>
  <img src="@/assets/banner-girl.svg" alt="girl" class="banner-girl"/>
  <div class="banner-navigation">
    <div class="banner-leftside"><img src="@/assets/banner-leftside.svg" alt="arrow-to-the-left"/></div>
  <button class="banner-button">Подробнее о салоне</button>
  <div class="banner-rightside"><img src="@/assets/banner-rightside.svg" alt="arrow-to-the-right"/></div>
</div>
</div>
</div>

</template>

<script setup>

</script>
<style scoped>
.banner {
  background: url('@/assets/banner-background.svg'), lightgray -0.505px -340px / 100.07% 141.697% no-repeat;
  margin-top: -140px;
width: 100%;
z-index: 1;

}
.banner-content {
  padding-top: 100px;
}
.banner-logo {
  color: #FFF;
font-family: 'Krona One', sans-serif;
font-size: 227px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-transform: uppercase;
position: absolute;
margin: 364px 48px 0;
}
.banner-description1 {
  width: 390px;
  color: #37384C;
font-family: Circe;
font-size: 40px;
font-style: normal;
font-weight: 400;
line-height: 50.3px; /* 125.75% */
text-transform: uppercase;
position: absolute;
margin: 180px 0 0 84px;
}
.banner-description2 {
  width: 251px;
  color: #37384C;
font-family: Circe;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 151.023%; /* 24.164px */
position: absolute;
margin-top: 210px;
right: 98px;
}
.banner-girl {
  position: relative;
}
.banner-navigation {
  position: absolute;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
top: 712px;

}
.banner-button {

  color: #FFF;
text-align: center;
/* leading-trim: both;
text-edge: cap; */
font-family: Circe;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 50.3px; /* 314.375% */
text-transform: uppercase;
width: 259px;
height: 60px;
flex-shrink: 0;
border-radius: 58px;
background: #37384C;
align-items: center;

}
.banner-button:hover {
  color: #37384C;
  background: #FFF;
  cursor: pointer;
}
.banner-leftside {

margin-left: 86px;
}
.banner-rightside {

  margin-right: 80px;
}
.banner-leftside, .banner-rightside {
  cursor: pointer;
}
.banner-bubble {
position: absolute;
right: -250px;
top: -250px;
}
  </style>
