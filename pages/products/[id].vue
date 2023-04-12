<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Some random text goes here.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params;
</script>

<style scoped>

</style>