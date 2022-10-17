<template>
        <div class="columns is-vcentered is-centered">
            <div class="column first-column">
                <Navbar/>
 
                <img src="https://indiehoy.com/wp-content/uploads/2021/07/moonrise-kingdom.jpg" class="image-cover">
            </div>

            <div class="column">
                <p class="is-size-3 welcome-text">As portas do mundo cinematográfico estão abertas para você, conheça pessoas com o mesmo amor e paixão pelo cinema.</p>
            </div>

            <YellowButton/>
        </div>
    
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Navbar from './components/Navbar.vue';
    import YellowButton from './components/YellowButton.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Navbar,
            YellowButton
        }
    })
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Special+Elite&display=swap');

    .columns {
        height: 100vh;
        
    }

    .first-column {
        height: 50%;
    }

    .image-cover {
        width: 100%;
        height: 100%;
    }

    .welcome-text {
        font-family: 'Special Elite', cursive;
    }

    .image-cover {
        width: 400px;
    }


</style>
