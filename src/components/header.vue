<script setup>

</script>

<template>
  <div class="storeHeader">
    <div class="burger">
        <img src="/src/img/burger.svg" alt="">
    </div>
    <div class="logoName">
        <img src="/src/img/logo.png" alt="">
        <h1>Store</h1>
    </div>
    <div class="listProducts">

    </div>
    
    <ul>
        <li><a href="#products">Products</a></li>
        <li><a href="#about-store">About store</a></li>
        <li><a href="#prices">Prices</a></li>
    </ul>
  </div>
</template>

<style scoped>
    .storeHeader {
        padding: 10px 0 10px 0;
        display: flex;
        align-items: center;
        background-color: rgb(0, 0, 0);
        color: white;
    }

    .burger {
        width: 30px;
        height: 30px;
    }

    .burger img {
        width: 100%;
        height: 100%;
        background-size: contain;
    }

    .logoName {
        display: flex;
        align-items: center
    }

    .logoName img {
        width: 50px;
        height: 50px;
    }

    .logoName h1 {
        margin: 0px 0px 0px 5px;
    }

    .listProducts {
        width: 140px;
        height: 40px;
        border-color: white;
        border-radius: 10px;
        border: 1px solid #ffffff;
    }

    ul {
        display: flex;
        align-items: center
    }

    li {
        margin: 0 5px 0 5px;
        list-style: none;
    }
</style>
