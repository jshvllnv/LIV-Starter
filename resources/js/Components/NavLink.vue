<script setup>
defineProps({
    routeName: String,
});
</script>

<template>
    <Link :href="route(routeName)" class="text-decoration-none text-white">
        <slot />
    </Link>
</template>
