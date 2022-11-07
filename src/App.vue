<template>
        <Home/>
        <InfoMeetings/>
        <Movie/>
        <Team/>
        <Footer/>
    
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Home from './screens/Home.vue';
    import Movie from './screens/Movie.vue';
    import InfoMeetings from './screens/InfoMeetings.vue';
    import Team from './screens/Team.vue';
    import Footer from './screens/Footer.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Home,
            Movie,
            Team,
            InfoMeetings,
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

    body::-webkit-scrollbar {
        width: 18px;
      }
      body::-webkit-scrollbar-track {
        background: black;
      }
      
      body::-webkit-scrollbar-thumb {
        background-color: white;
        border-radius: 8px;
        border: 5px solid transparent;
        background-clip: content-box;
      }
      
</style>
