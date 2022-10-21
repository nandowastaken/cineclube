<template>
    <div class="columns is-vcentered home">
        <div class="column">
            <Navbar/>
            <img src="https://indiehoy.com/wp-content/uploads/2021/07/moonrise-kingdom.jpg" class="image-cover"> 
        </div>

        <div class="column">
            <div class="content-welcome">
                <p class="welcome-text">
                    As portas do mundo cinematográfico estão abertas para você, conheça pessoas com o mesmo amor e paixão pelo cinema.
                </p>

                <YellowButton message="Junte-se ao Clube"/>
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
    @import url('https://fonts.googleapis.com/css2?family=Special+Elite&display=swap');
    .home {
        background-color: black;
    }

    .image-cover {
        width: 100vw;
        height: 50vh;
    }

    .content-welcome {
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 30px;
    }

    .welcome-text {
        font-family: 'Special Elite', cursive;
        color: white;
        font-size: 1.7rem;
        margin-left: 20px;
        
    }

</style>
