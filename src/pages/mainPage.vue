<script setup>
import Menu from '../components/menu.vue';
import HomePage from './homePage.vue';
</script>
<template>
    <div class="main_page_container">
        <div class="content">
            <HomePage></HomePage>
        </div>
        <div class="menu">
            <Menu></Menu>
        </div>
    </div>
</template>
<style scoped>
    .main_page_container {
        background-color: var(--white);
        height: 80%;
        width: 20rem;
        box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
        border-radius: 1.5rem;
        display: grid;
        
        grid-template-columns: 1fr;
        grid-template-rows: 1fr 4rem;

        grid-template-areas: 
            "content"
            "menu";

        overflow: hidden;
    }

    .content{
        background-color: blu;
        grid-area: content;
    }
    .menu{
        grid-area: menu;
    }
</style>