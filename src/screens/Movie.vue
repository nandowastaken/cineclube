<template>
    <div class="columns movie">
        <div class="column is-centered">
            <img src="https://miro.medium.com/max/1400/1*Q4LG9I7iN6mNO5kWJe6hLg.jpeg" class="movie-cover">
        </div>

        <div class="column">
            <div class="content-movie">
                <div class="movie-header">
                    <h1 class="movie-title">O Castelo Animado</h1>
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
        name: 'YellowButton',
        
    });

</script>

<style>
    .movie {
        background-color: black;
    }
    .movie-cover {
        height: 50vh;
    }

    .movie-title {
        font-family: "Inter", sans-serif;
        color: white;
        font-weight: 700;
        font-size: 32px;
    }

    .movie-info {
        color: #BFBFBF;
        opacity: 0.6;
    }

    .sinopse {
        color: white;
        font-family: "Inter", sans-serif;
        margin: 0px 35px;
        font-weight: 400;
        font-size: 18px;
    }

    .content-movie {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        gap: 15px;
    }
</style>