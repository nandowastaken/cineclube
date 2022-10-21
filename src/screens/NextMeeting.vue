<template>
    <div class="columns next-meeting">
        <div class="column">
            <div class="content-next-meeting">
                <h1 class="next-meeting-title">Próxima Reunião</h1>
                <p class="next-meeting-description">
                    Nossa próxima reunião é Sexta-feira, 11/11. E o filme é O Castelo Animado, do Studio Ghibli.
                </p>
                <YellowButton message="Ver Filme"/>
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
    .next-meeting {
        background-color: black;
    }

    .content-next-meeting {
        display: flex;
        flex-direction: column;
        text-align: center;
        gap: 10px;
        margin: 10px;
    }

    .next-meeting-title, .next-meeting-description {
        font-family: 'Inter', sans-serif;
        color: rgb(255, 255, 255);
    }

    .next-meeting-title {
        font-size: 30px;
        font-weight: 700;
        
    }

    .next-meeting-description {
        font-size: 20px;
        font-weight: 400;

    }


</style>