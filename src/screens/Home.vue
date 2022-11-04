<template>
    <div class="columns is-vcentered home">
        <div class="column home-cover">
            <Navbar/>
            <img src="https://starwarsblog.starwars.com/wp-content/uploads/2017/03/darth-vader-1-cover-header.jpg" class="image-cover-mobile"> 
            <img src="https://starwarsblog.starwars.com/wp-content/uploads/2017/03/darth-vader-1-cover-header.jpg" alt="" class="image-cover-desktop">
        </div>

        <div class="column">
            <div class="content-welcome">
                <p class="welcome-text">
                    As portas do mundo cinematográfico estão abertas para você, conheça pessoas com o mesmo amor e paixão pelo cinema.
                </p>

                <a href="https://docs.google.com/forms/d/e/1FAIpQLSe3-J5YLM8g4xVSOLnHmfYY8NCosW4-q_QF26D6PvtF2KjmBw/viewform?usp=sf_link" target="blank">
                    <MovieButton message="Junte-se ao Clube" />
                </a>
            </div>
            
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Navbar from '../components/Navbar.vue';
    import MovieButton from '../components/MovieButton.vue';

    export default defineComponent({
        name: 'HomeScreen',
        components: {
            Navbar,
            MovieButton
        }
    })
</script>

<style>
    @import '../assets/styles/home.css';

</style>
