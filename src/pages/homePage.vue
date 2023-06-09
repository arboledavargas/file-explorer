<script setup>
import StorageMeter from "../components/storage-meter.vue";
</script>
<template>
    <div class="home_container">
        <div class="header">
            <div class="icon"><i class="las la-search"></i></div>
            <div class="icon"><i class="las la-sliders-h"></i></div>
            <div class="icon"><i class="lar la-user"></i></div>
        </div>
        <div class="content">
            <StorageMeter></StorageMeter>
        </div>
    </div>
</template>
<style scoped>
    .home_container {
        height: 100%;
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows: 5rem 1fr;
        grid-template-areas: 
            "header"
            "content";
    }

    .header {
        grid-area: header;
        display: flex;
        align-items: center;
        justify-content: flex-end;
        align-items: center;
    }

    .icon {
        font-size: 24px;
        color: var(--light-gray);
        padding: 1rem;
    }

    .icon:hover {
        color: var(--royal-blue);
    }
</style>