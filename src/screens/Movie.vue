<template>
    <div class="columns movie">
        <div class="column is-centered">
            <img src="https://www.silvanatoazza.com.br/cms/_files/general/835f0bae.jpg" class="movie-cover" id="movie">
        </div>

        <div class="column">
            <div class="content-movie">
                <div class="movie-header">
                    <h1 class="movie-title" id="month-movie">Psicose</h1>
                    <p class="movie-info">1960 - Terror/Thriller - 109min</p>
                </div>
                
                <p class="sinopse">Uma mulher rouba uma fortuna de homem milionário e entra em uma fuga, paranoica em ser pega, o desconforto é transmitido na trama, até ela eventualmente conhecer um sujeito dono de um hotel um tanto que suspeito.</p>
            </div>
            
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'MovieMonth',
        
    });

</script>

<style>
    @import '../assets/styles/movie.css';
</style>
