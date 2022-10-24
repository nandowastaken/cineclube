<template>
    <div class="columns is-vcentered home">
        <div class="column home-cover">
            <Navbar/>
            <img src="https://indiehoy.com/wp-content/uploads/2021/07/moonrise-kingdom.jpg" class="image-cover-mobile"> 
            <img src="https://i.pinimg.com/originals/07/c7/2e/07c72e9d829041fe210215dc4d60cbe0.jpg" alt="" class="image-cover-desktop">
        </div>

        <div class="column">
            <div class="content-welcome">
                <p class="welcome-text">
                    As portas do mundo cinematográfico estão abertas para você, conheça pessoas com o mesmo amor e paixão pelo cinema.
                </p>

                <a href="https://docs.google.com/forms/d/e/1FAIpQLSe3-J5YLM8g4xVSOLnHmfYY8NCosW4-q_QF26D6PvtF2KjmBw/viewform?usp=sf_link" target="blank">
                    <YellowButton message="Junte-se ao Clube" />
                </a>
            </div>
            
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Navbar from '../components/Navbar.vue';
    import YellowButton from '../components/YellowButton.vue';

    export default defineComponent({
        name: 'HomeScreen',
        components: {
            Navbar,
            YellowButton
        }
    })
</script>

<style>
    @import '../assets/styles/home.css';

</style>
