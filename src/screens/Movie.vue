<template>
    <div class="columns movie">
        <div class="column is-centered">
            <img src="https://1.bp.blogspot.com/--yFt3tTvX9E/XzWgMR_AJwI/AAAAAAAALYs/e-JEPoAIFM8SPoD2rXq8LJU1uD85KawdgCLcBGAsYHQ/s1150/Psycho-1960-001.jpg" class="movie-cover" id="movie">
        </div>

        <div class="column">
            <div class="content-movie">
                <div class="movie-header">
                    <h1 class="movie-title" id="month-movie">Psicose</h1>
                    <p class="movie-info">1960 - Terror/Thriller - 109min</p>
                </div>
                
                <p class="sinopse">Em Psicose, Marion Crane (Janet Leigh) é uma secretária que rouba 40 mil dólares da imobiliária onde trabalha para se casar e começar uma nova vida. Durante a fuga a carro, ela enfrenta uma forte tempestade, erra o caminho e chega em um velho hotel. O estabelecimento é administrado por um sujeito atencioso chamado Norman Bates (Anthony Perkins), que nutre um forte respeito e temor por sua mãe. Marion decide passar a noite no local, sem saber o perigo que a cerca.</p>
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
