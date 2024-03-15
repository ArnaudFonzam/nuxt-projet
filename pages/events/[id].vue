<script setup>
    const route = useRoute();
    console.log(route.params.id);
</script>
<template>
    <div class="text-3xl font-bold underline">
        <p> Events id: {{ $route.params.id }} </p>
    </div>
</template>