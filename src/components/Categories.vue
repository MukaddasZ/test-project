<template>
    <div class="categories">
        <img src="@/assets/bubble.svg" alt="bubble" class="categories-bubble" />
        <img src="@/assets/categories-line.svg" alt="line" class="categories-line" />
        <div class="categories-content container">
            <img src="@/assets/left-slide.svg" alt="left-slide" class="categories-left-slide" />
            <div class="categories-title">
            <p>Категории</p>
            </div>
            <img src="@/assets/right-slide.svg" alt="right-slide" class="categories-right-slide" />
        </div>
        <div class="categories-items">
        <CategoriesItems
        v-for="item of items"
        :key="i"
        :img="item.img"
        :title="item.title"
      />
    </div>
    </div>
    
</template>
<script>
import CategoriesItems from './CategoriesItems.vue';
import { ref } from 'vue';

export default {
  name: "Categories",
  components: { CategoriesItems },
  data() {
    return {
      items: [
        {
            img: '/src/assets/hairdressing.svg',
            title: 'Парикмахерские услуги',
        },
        {
            img: '/src/assets/nail-service.svg',
            title: 'Ногтевой сервис',
        },
        {
            img: '/src/assets/bodycare.svg',
            title: 'Уход за телом',
        },
        {
            img: '/src/assets/depilation.svg',
            title: 'Удаление волос',
        },
        {
            img: '/src/assets/tattoo-piercing.svg',
            title: 'Тату и пирсинг',
        },
        {
            img: '/src/assets/makeup.svg',
            title: 'Макияж',
        },
    ]
    }
},
}


</script>
<style>
.categories {
    background: url('./src/assets/categories-background.svg');
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: -188px;
    /* z-index: 10; */
    position: relative;
height: 843px;
flex-shrink: 0;
}
.categories-line {
width: 115px;
height: 3px;
flex-shrink: 0;
stroke-width: 9px;
stroke: rgba(201, 196, 200, 0.16);
padding-top: 56px;
position: absolute;
color: #C9C4C829;


}
.categories-content {
    display: grid;
    grid-template-columns: 60px auto 60px;
    column-gap: 80px;
    justify-items: center;
    margin: 118px 80px 0;
    width: 100%;
    max-width: 1160px;
}
.categories-title p {
    color: #FFF;
font-family: Circe;
font-size: 50px;
font-style: normal;
font-weight: 400;
line-height: 50.3px; /* 100.6% */
text-transform: uppercase;
}
.categories-bubble {
    position: absolute;
    left: 86px;
    top: -286px;
}
.categories-items {
margin: 90px 80px 128px;
display: flex;
justify-content: space-between;
gap: 16px;

}
</style>
