<script setup>
defineProps({
    routeName: String,
    componentName: String,
});
</script>

<template>
    <Link
        :href="route(routeName)"
        class="text-decoration-none text-white"
        :class="{ 'bg-success': $page.component === componentName }"
    >
        <slot />
    </Link>
</template>
