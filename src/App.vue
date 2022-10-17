<template>
        <Home/>
    
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Home from './screens/Home.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Home
        }
    })
</script>

<style>

</style>
