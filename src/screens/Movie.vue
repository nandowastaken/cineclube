<template>
    <div class="columns movie">
        <div class="column is-centered">
            <img src="https://miro.medium.com/max/1400/1*Q4LG9I7iN6mNO5kWJe6hLg.jpeg" class="movie-cover" id="movie">
        </div>

        <div class="column">
            <div class="content-movie">
                <div class="movie-header">
                    <h1 class="movie-title" id="month-movie">O Castelo Animado</h1>
                    <p class="movie-info">2004 - Fantasia/Aventura - 119min</p>
                </div>
                
                <p class="sinopse">Uma bruxa lança uma terrível maldição sobre a jovem Sophie transformando-a numa velha de 90 anos. Desesperada, ela embarca numa odisseia em busca do Castelo Andante, onde reside um misterioso feiticeiro que poderá ajudá-la a reverter o feitiço.</p>
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