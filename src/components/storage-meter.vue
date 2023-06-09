<script setup>
import LightButton from "./light-button.vue";
</script>
<template>
<div class="storage-meter-container">
    <div class="storage-chart"><i class="las la-chart-pie"></i><span>68%</span></div>
    <div class="details">
        <p><strong>10.8 GB</strong><span>of</span></p>
        <LightButton>Buy Storage</LightButton>
    </div>
</div>
</template>
<style>
    .storage-meter-container {
        display: flex;
        background-color: var(--royal-blue);
        border-radius: 1rem;
        overflow: hidden;
        max-width: 100%;
        padding: 1rem;
        margin: 1rem;
    }

    .details {
        display: inline-block;
    }

    .details button {
        
    }
</style>