<script setup>

</script>
<template>
    <button class="light_button">
        <slot></slot>
    </button>
</template>
<style scoped>
    .light_button {
        background-color: var(--cornflower-blue);
    }
</style>