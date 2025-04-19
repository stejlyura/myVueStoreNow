<script setup>

</script>

<template>
    <div class="store_header">
        <div class="menu">
            <span></span>
            <span></span>
        </div>
        <h1>GRAPHICS CARD</h1>
        <button class="cart"><h2>Shop now</h2></button>
    </div>
</template>

<style scoped>
    .store_header {
        margin-top: 20px;
        display: flex;
        width: 100%;
        height: 73px;
        font-family: Sour_Gummy;
        align-items: center;
        justify-content: space-around;
    }

    h1 {
        font-weight: 700;

    }

    .menu {
        width: 103px;
        height: 80%;;
        border: 7px solid var(--blueCollor);
        border-radius: var(--border18);
        background-color: var(--yellowColor);
        display: flex;
        align-items: center;
        justify-content: space-around;
        flex-direction: column;
        cursor: pointer;
    }

    .menu span {
        display: block;
        width: 50%;
        height: 10px;
        background-color: var(--blueCollor);
        border-radius: var(--border18);
    }

    .cart {
        font-family: Sour_Gummy;
        min-width: 103px;
        height: 80%;
        padding: 0 5px 0 5px;
        background-color: var(--yellowColor);
        border: 7px solid var(--blueCollor);
        border-radius: var(--border18);
        cursor: pointer;
    }
</style> 
