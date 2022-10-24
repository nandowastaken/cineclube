<template>
    <div class="columns next-meeting">
        <div class="column">
            <div class="content-next-meeting">
                <h1 class="next-meeting-title" id="next-meeting">Próxima Reunião</h1>
                <p class="next-meeting-description">
                    Nossa próxima reunião é Sexta-feira, 18/11, sobre o filme Psicose (1960), do Alfred Hitchcock.
                </p>
                <a href="#movie">
                    <YellowButton message="Ver Filme"/>
                </a>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import YellowButton from '../components/YellowButton.vue';

    export default defineComponent({
        name: 'HowWeWork',
        components: {
            YellowButton,
        }
    })
</script>

<style>
    @import '../assets/styles/next-meeting.css';
</style>