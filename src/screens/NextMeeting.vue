<template>
    <div class="columns next-meeting">
        <div class="column">
            <div class="content-next-meeting">
                <h1 class="next-meeting-title" id="next-meeting">Próxima Reunião</h1>
                <p class="next-meeting-description">
                    Nossa próxima reunião nessa Sexta-feira, 23/12, onde iremos ter uma seção de cinema e assistiremos A Origem dos Guardiões (2012) no Ifal de 13:00 :)
                </p>

                <a href="#movie">
                    <MovieButton message="Ver Filme"/>
                </a>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import MovieButton from '../components/MovieButton.vue';

    export default defineComponent({
        name: 'HowWeWork',
        components: {
            MovieButton,
        }
    })
</script>

<style>
    @import '../assets/styles/next-meeting.css';
</style>
