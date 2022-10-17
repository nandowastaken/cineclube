<template>
   <div class="columns is-vcentered is-centered">
        <div class="column first-column">
            <Navbar/>
            <img src="https://indiehoy.com/wp-content/uploads/2021/07/moonrise-kingdom.jpg" class="image-cover">
        </div>

        <div class="content-welcome">
            <div class="column welcome-paragraph">
                <p class="welcome-text">As portas do mundo cinematográfico estão abertas para você, conheça pessoas com o mesmo amor e paixão pelo cinema.</p>
            </div>

            <YellowButton/>
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
    @import url('https://fonts.googleapis.com/css2?family=Special+Elite&display=swap');

    .columns {
        background-color: black;
        width: 100%;
    }

    .first-column {
        width: 100%;
        height: 50%;
    }

    .image-cover {
        height: 100%;
        width: 100%;
        max-width: 800px;
    }

    .content-welcome {
        height: 50%;
    }

    .welcome-paragraph {
        margin: auto;
        width: 90%;
    }

    .welcome-text {
        font-family: 'Special Elite', cursive;
        color: white;
        font-size: 1.7rem;
        margin-bottom: 10px;
    }

    .image-cover {
        width: 400px;
    }

</style>
