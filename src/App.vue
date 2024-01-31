<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
    // Logica Javascript
    name: 'VueApp',

    components: {
        AppTitle,
        AppHero
    }
};
</script>

<template>
    <!-- Template -->
    <AppTitle />
    <AppHero />
</template>

<style>
/* Style */

.container {
    max-width: 1080px;
    margin: 0 auto;
    text-align: center;
}

img {
    max-width: 100%;
    margin: 0 auto;
}
</style>