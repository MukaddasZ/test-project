<template>
<div class="header-menu">
  <div class="menu-main">
    <img src="@/assets/menu-line.svg" alt="menu-line" class="menu-line"/>
<p>меню</p>
</div>
</div>



</template>

<script>

</script>



<style scoped>
.header-menu {
  margin: 20px auto;
  z-index: 100;
  width: 100%;
  max-width: 1360px;
height: 88px;
flex-shrink: 0;
position: relative;
border-radius: 22px;
/* border: 1px solid rgba(0, 0, 0, 0.10);

backdrop-filter: blur(17px); */
}

.menu-main {
display: flex;
justify-content: center;
align-items: center;
gap: 18px;
width: 130px;
height: 50px;
flex-shrink: 0;
border-radius: 58px;
border: 2px solid #37384C;
margin: 35px 10px 0 40px;


}
.menu-main p {
color: #37384C;
 font-size: 16px;
 font-family: Circe;
 font-weight: 700;
 text-transform: uppercase;
 line-height: 50.30px;
 word-wrap: break-word;


}

</style>
