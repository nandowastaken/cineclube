<template>
        <Home/>
        <AboutUs/>
        <HowWeWork/>
        <NextMeeting/>
        <Movie/>
        <Team/>
        <Footer/>
    
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Home from './screens/Home.vue';
    import AboutUs from './screens/AboutUs.vue';
    import HowWeWork from './screens/HowWeWork.vue';
    import NextMeeting from './screens/NextMeeting.vue';
    import Movie from './screens/Movie.vue';
    import Team from './screens/Team.vue';
    import Footer from './screens/Footer.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Home,
            AboutUs,
            HowWeWork,
            NextMeeting,
            Movie,
            Team,
            Footer
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
