<script setup>
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div class="min-h-screen flex flex-col sm:justify-center items-center pt-6 sm:pt-0 bg-gray-100 dark:bg-gray-900"
        style="background-image: url('background2.jpg'); background-size: cover;">
        <div>
            <Link href="/">
            <ApplicationLogo class="w-20 h-20" />
            </Link>
        </div>

        <div
            class="h-[500px] w-[700px] ml-24 px-6 py-4 bg-white  dark:bg-gray-800 shadow-md overflow-hidden sm:rounded-lg">
            <slot />
        </div>
    </div>
</template>
