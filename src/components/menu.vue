<script setup>

</script>

<template>
    <div class="menu_container">
        <div class="icon"><i class="las la-home"></i></div>
        <div class="icon"><i class="lar la-folder-open"></i></div>
        <div class="icon"><i class="lar la-clock"></i></div>
        <div class="icon"><i class="las la-trash"></i></div>
    </div>
</template>

<style scoped>
    .menu_container {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        height: 100%;
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