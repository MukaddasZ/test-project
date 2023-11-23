<template>
    <div class="categories">
        <img src="@/assets/bubble.svg" alt="bubble" class="categories-bubble" />
        <img src="@/assets/categories-line.svg" alt="line" class="categories-line" />
        <div class="categories-content">
            <img src="@/assets/left-slide.svg" alt="left-slide" class="categories-left-slide" />
            <div class="categories-title">
            <p>Категории</p>
            </div>
            <img src="@/assets/right-slide.svg" alt="right-slide" class="categories-right-slide" />
        </div>
    </div>
</template>
<script>
</script>
<style>
.categories {
    background: url('./src/assets/categories-background.svg');
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: -188px;
    z-index: 10;
    position: relative;
    width: 1440px;
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
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 118px;
    width: 100%;
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
</style>
