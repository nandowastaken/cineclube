<template>
        <Home/>
        <AboutUs/>
        <HowWeWork/>
        <NextMeeting/>
    
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Home from './screens/Home.vue';
    import AboutUs from './screens/AboutUs.vue';
    import HowWeWork from './screens/HowWeWork.vue';
    import NextMeeting from './screens/NextMeeting.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Home,
            AboutUs,
            HowWeWork,
            NextMeeting
        }
    })
</script>

<style>


    #app {
        height: 100vh;
        width: 100vw;
        background-color: black;
        
    }
</style>
