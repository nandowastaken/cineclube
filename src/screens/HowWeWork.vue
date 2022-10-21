<template>
    <div class="columns how-we-work">
        <div class="column">
            <div class="content-how-we-work">
                <h1 class="how-we-work-title">Como funciona?</h1>
                <p class="how-we-work-description">
                    Todo mês nós temos duas reuniões em uma Sexta-feira, uma no turno da manhã e a outra na da tarde, sobre um filme escolhido previamente. O tema e a data serão sempre exibidos neste site, então não precisam ficar preocupados em ficarem desinformados.
                </p>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'HowWeWork',
        components: {

        }
    })
</script>

<style>
    .how-we-work {
        background-color: white;
    }

    .content-how-we-work {
        display: flex;
        flex-direction: column;
        gap: 10px;
        margin: 10px;
    }

    .how-we-work-title, .how-we-work-description {
        font-family: 'Inter', sans-serif;
        color: rgb(0, 0, 0);
    }

    .how-we-work-title {
        font-size: 30px;
        font-weight: 700;
        
    }

    .how-we-work-description {
        font-size: 20px;
        font-weight: 400;

    }
</style>