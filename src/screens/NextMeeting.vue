<template>
    <div class="columns next-meeting">
        <div class="column">
            <div class="content-next-meeting">
                <h1 class="next-meeting-title" id="next-meeting">Próxima Reunião</h1>
                <p class="next-meeting-description">
                    Nossa próxima reunião é Sexta-feira, 25/11, sobre o filme Psicose (1960), do Alfred Hitchcock, nos horários da manhã
                    de 11h até 12h, e de tarde, de 13h até 14h.
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