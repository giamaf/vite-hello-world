<script>
export default {
    name: 'AppJumbo',

    data: () => ({
        jumboImage: 'vue.svg',

    }),
    methods: {
        createPath(jumboImage) {
            const url = new URL(`../assets/${jumboImage}`, import.meta.url)

            return url.href;
        }
    }
}
</script>

<template>
    <img :src="createPath(jumboImage)" alt="logo-vue">
</template>

<style></style>