<script setup>

</script>

<template>
  <div class="storeHeader">
    <div class="logoName">
        <img src="/src/img/Group 1.svg" alt="">
        <h1>Store</h1>
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
    justify-content: space-around;
    background-color: lightgreen;
}

.logoName {
    display: flex;
    align-items: center
}

.logoName h1 {
    margin: 0px 0px 0px 5px;
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
