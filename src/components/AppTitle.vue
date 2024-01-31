<script>
export default {
    name: 'pageTitle',
    data: () => ({
        textTitle: 'La mia prima app con Vite!',
    })
}
</script>

<template>
    <h1>{{ textTitle }}</h1>
</template>

<style>
h1 {
    text-align: center;
}
</style>