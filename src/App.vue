<template>
    <div class="page">
        <div class="columns">
            <div class="column">
                <Navbar/>
                <figure class="image is-1by1">
                    <img src="https://indiehoy.com/wp-content/uploads/2021/07/moonrise-kingdom.jpg">
                </figure>
            </div>

            <div class="column">
                <p class="is-size-3">As portas do mundo cinematográfico estão abertas para você, conheça pessoas com o mesmo amor e paixão pelo cinema.</p>
            </div>

            <div class="column">
                <button class="button">Junte-se ao Clube</button>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import Navbar from './components/Navbar.vue';

    export default defineComponent({
        name: 'App',
        components: {
            Navbar,
        }
    })
</script>

<style>
    .page {
        height: 100vh;
        background-color: black;
    }

</style>
