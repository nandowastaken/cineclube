<template>
    <div class="columns team">
        <div class="column">
            <div class="team-member">
                <h1 class="team-title" id="team">Equipe</h1>

                <div class="members">
                    <div class="member">
                        <div class="box-container">
                            <img src="../assets/members-photos/Fernando.png" alt="" class="member-photo">
                            <div class="info-member">
                                <div class="member-header">
                                    <h1 class="member-name">Fernando Jorge</h1>
                                    <p class="member-function">presidente</p>
                                </div>
                                        
                                <p class="member-description">Presidente do Cineclube desde Março de 2022. Adora Star Wars e por um milagre não botou o Darth Vader na capa quando criou esse site.</p>
                            </div>
                        </div>
                    </div>
                        
                </div>

                <div class="members">
                    <div class="member">
                        <div class="box-container">
                            <img src="../assets/members-photos/Malu.png" alt="" class="member-photo">
                            <div class="info-member">
                                <div class="member-header">
                                    <h1 class="member-name">Malu Alaquoke</h1>
                                    <p class="member-function">mediadora</p>
                                </div>
                                        
                                <p class="member-description">Fã número 1 do Wes Anderson, adora filmes de guerra, drama e fantasia. Vive de Cup Noodles e Brooklyn 99.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="members">
                    <div class="member">
                        <div class="box-container">
                            <img src="../assets/members-photos/Lywya.png" alt="" class="member-photo">
                            <div class="info-member">
                                <div class="member-header">
                                    <h1 class="member-name">Lywya Eugênia</h1>
                                    <p class="member-function">designer</p>
                                </div>
                                        
                                <p class="member-description">obcecada pela lana del rey, twice e taylor swift. passatempo: ver filme cult para logar no letterboxed e hater número 1 do tarantino.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="members">
                    <div class="member">
                        <div class="box-container">
                            <img src="../assets/members-photos/MariaIsabel.png" alt="" class="member-photo">
                            <div class="info-member">
                                <div class="member-header">
                                    <h1 class="member-name">Maria Isabel</h1>
                                    <p class="member-function">designer</p>
                                </div>
                                        
                                <p class="member-description">Bel, aspirante a designer, ama falar mal de adaptações literárias e é obcecada por orgulho e preconceito.</p>
                            </div>
                        </div>
                        
                </div>
                
                </div>

                
                
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

    .members {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }

    .member {
        display: flex;
        flex-direction: row;
        margin: 15px;
    }

    .info-member {
        margin-left: 10px;
        padding: 3px;
    }

    .member-photo {
        width: 37%;
        border-radius: 20px 0px 0px 20px;
    }

    .member-name, .member-function, .member-description {
        color: black;
    }

    .member-name {
        font-family: "Inter", sans-serif;
        font-size: 24px;
        font-weight: 700;
        margin-bottom: 0;
        
    }

    .member-function {
        opacity: 0.8;
        font-family: 'Inter', sans-serif;
        font-style: italic;
        font-weight: 200;
        position: relative;
        bottom: 10px;
    }
    
    .member-description {
        font-family: "Inter", sans-serif;
        font-size: 15px;
        font-weight: 350;
        position: relative;
        bottom: 9px;
        line-height: normal;
        
    }

    .box-container {
        display: flex;
        border-radius: 20px;
        background-color: rgb(255, 255, 255);
    }

    
</style>