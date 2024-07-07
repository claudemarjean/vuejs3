<template>
    <h1>Hello world</h1>
    {{ props.subTitle }}
</template>

<script setup>
    const props  = defineProps(['subTitle']);
</script>