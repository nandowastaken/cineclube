<template>
    <div class="columns team">
        <div class="column">
            <div class="team-member">
                <h1 class="team-title" id="team">Equipe</h1>
                <MemberCard
                    name="Fernando Jorge"
                    position-member="presidente"
                    description="Presidente do Cineclube desde Março de 2022. Adora Star Wars e por um milagre não botou o Darth Vader na capa quando criou esse site."
                    image="Fernando.jpg"
                />
                <MemberCard
                    name="Malu Alaquoke"
                    position-member="mediadora"
                    description="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
                />
                <MemberCard
                    name="Lywya Eugênia"
                    position-member="designer"
                    description="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
                />
                
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    import MemberCard from '../components/MemberCard.vue';

    export default defineComponent({
        name: 'TeamCine',
        components: {
            MemberCard
        }
        
    });
</script>

<style>
    .team {
        background-color: black;
    }

    .team-title {
        color: white;
        font-size: 30px;
        font-weight: 700;
        text-align: center;
        font-family: "Inter", sans-serif;
    }

    
</style>