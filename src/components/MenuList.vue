<template>
<div class="menu-list">
  <a href="element.path" v-for="(element, i) of menu" :key="i">
          {{ element.name }} 
        </a>
    
</div>
</template>
<script>
export default {
  name: "Menu",
  data() {
    return {
     
      menu: [
        {
          name: "все",
          path: "/all",
       
        },
        {
          name: "парикмахерские",
          path: "/hairdressing",
        },
        {
          name: "маникюр",
          path: "/manicure",
        },
        {
          name: "педикюр",
          path: "/pedicure",
        },
        {
          name: "макияж",
          path: "/makeup",
        },
        {
          name: "удаление волос",
          path: "/depilation",
        },
        {
          name: "косметология",
          path: "/cosmetology",
        },
        {
          name: "ресницы",
          path: "/eyelashes",
        },
      ],
    };
  },
}
</script>

<style scoped>
.menu-list {
  margin-top: 112px;
  display: flex;
  gap: 8px;
  align-items: center;
  margin-left: 80px;


}
.menu-list a {
  color: #000;
/* leading-trim: both;
text-edge: cap; */
font-family: Circe;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 22.853px; /* 142.829% */
text-transform: uppercase;
 flex-shrink: 0;
text-decoration: none;
/* height: 54px; */
border-radius: 87px;
border: 1px solid rgba(55, 56, 76, 0.21);
background: rgba(255, 255, 255, 0.00);
padding: 18px 30px;
}
/* .menu-list a:first-child {


} */
.menu-list a:hover {
  color: #FFF;
text-align: center;
/* leading-trim: both;
text-edge: cap; */
font-family: Circe;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 22.853px; /* 142.829% */
text-transform: uppercase;
border-radius: 87px;
background: #37384C;
}

</style>
