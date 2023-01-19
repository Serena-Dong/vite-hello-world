<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
    data() {
        return {
        }
    },
    components: {
        AppTitle,
        AppHero
    }
}
</script>

<template>
    <app-title></app-title>
    <AppHero></AppHero>
</template>

<style scoped>
h1 {
    color: green;
}
</style>
