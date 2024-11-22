<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <div class="hero bg-base-700 min-h-screen">
        <div class="hero-content flex-col lg:flex-row">
            <img src="https://img.daisyui.com/images/stock/photo-1635805737707-575885ab0820.webp"
                class="max-w-lg rounded-sm shadow-sm" />
            <div>
                <h1 class="text-5xl font-bold">Yoosup</h1>
                <p class="py-6">
                    Yoosup is a platform that allows you to connect with your friends and family. You can chat, call,
                    and
                    video call with your loved ones.
                </p>
                <RouterLink to="/contact">
                    <button class="btn btn-primary">contact me</button>
                </RouterLink>
            </div>
        </div>
    </div>
</template>

<style scoped></style>
