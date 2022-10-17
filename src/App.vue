<template>
        <Home/>
        <AboutUs/>
    
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Home from './screens/Home.vue';
    import AboutUs from './screens/AboutUs.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Home,
            AboutUs
        }
    })
</script>

<style>

</style>
