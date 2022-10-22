<template>
    <div class="columns team">
        <div class="column">
            <div class="team-member">
                <h1 class="team-title" id="team">Equipe</h1>
        
                <div class="member">
                    <div class="box-container"></div>
                    <div class="info-member">
                        <div class="member-header">
                            <h1 class="member-name">Fernando Jorge</h1>
                            <p class="member-function">presidente</p>
                        </div>
                        
                        <p class="member-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'TeamCine',
        
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

    .member {
        display: flex;
        flex-direction: row;
        margin: 15px;
    }

    .info-member {
        margin-left: 10px;
    }

    .member-name {
        color: white;
        font-family: "Inter", sans-serif;
        font-size: 26px;
        font-weight: 700;
        margin-bottom: 0;
        
    }

    .member-function {
        color: #FFFFFF;
        opacity: 0.8;
    }
    
    .member-description {
        font-family: "Inter", sans-serif;
        font-size: 14px;
    }

    .box-container {
        width: 320px;
        padding: 20px 20px;
        border: 5px solid gray;
        margin: 0;
        border-radius: 20px;
        background-color: gray;
    }
</style>