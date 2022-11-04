<template>
    <div class="columns movie">
        <div class="movieCardBox">
            <div class="movieCard">
                <div class="imgMovieBox">
                    <img src="https://www.silvanatoazza.com.br/cms/_files/general/835f0bae.jpg" id="movie" class="movieCoverMobile">
                    <img src="https://poltronanerd.com.br/wp-content/uploads/2018/01/Psicose-cena.jpg" id="movie" class="movieCoverDesktop">
                </div>

                <div class="infoMovie">
                    <p class="movieTitle">Psicose</p>
                    <p class="movieDate">1960 - Terror/Thriller - 109min</p>
                    <p class="movieSinopse">Uma mulher rouba uma fortuna de um homem milionário e entra em uma fuga, paranoica em ser pega, o desconforto é transmitido na trama, até ela eventualmente conhecer um sujeito dono de um hotel um tanto que suspeito.</p>
                </div>

                <div class="movieBoxInstruction">
                    Passe o mouse em cima
                </div>
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
