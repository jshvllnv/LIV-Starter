<script setup>
defineProps({
    routeName: String,
    label: String,
});
</script>

<template>
    <Link :href="route(routeName)" class="text-primary hover fw-bold underline">
        {{ label }}
    </Link>
</template>
