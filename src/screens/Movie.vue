<template>
    <div class="columns movie">
        <div class="movieCardBox" >
            <div class="movieCard" id="movie">
                <div class="imgMovieBox">
                    <img src="https://occ-0-768-114.1.nflxso.net/dnm/api/v6/E8vDc_W8CLv7-yMQu8KMEC7Rrr8/AAAABTdQEk1cq4XPU1JajVf4wRyzuRIamC6Ra_RBVVZfD2-o6B40layNHPvcj1BAx7zHIP69hlgr17WncZxvF-FM3qYJUl8LaVDPzImu.jpg?r=b82" class="movieCoverMobile">
                    <img src="https://occ-0-768-114.1.nflxso.net/dnm/api/v6/E8vDc_W8CLv7-yMQu8KMEC7Rrr8/AAAABTdQEk1cq4XPU1JajVf4wRyzuRIamC6Ra_RBVVZfD2-o6B40layNHPvcj1BAx7zHIP69hlgr17WncZxvF-FM3qYJUl8LaVDPzImu.jpg?r=b82" class="movieCoverDesktop">
                </div>

                <div class="infoMovie">
                    <div class="movieHeader">
                        <p class="movieTitle">A Origem dos Guardiões</p>
                        <p class="movieDate">2012 - Animação/Fantasia - 97min</p>
                    </div>
                    
                    <p class="movieSinopse">Jack Frost, um garoto que controla o inverno, se junta ao seleto time dos Guardiões Imortais para impedir Breu, o bicho-papão, de transformar todos os sonhos das crianças em pesadelo e usar seus poderes maquiavélicos para governar o mundo.</p>
                </div>

                <div class="movieBoxInstruction">
                    <p class="movieBoxInstructionText">Passe o mouse em cima</p>
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
