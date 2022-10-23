<template>
    <div class="member">
            <div class="box-container">
                <img src="../assets/members-photos/template.png" alt="" class="member-photo">
                <div class="info-member">
                    <div class="member-header">
                        <h1 class="member-name">{{ name }}</h1>
                        <p class="member-function">{{ positionMember }}</p>
                    </div>
                            
                    <p class="member-description">{{ description }}</p>
                </div>
            </div>
            
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'YellowButton',
        props: {
            name: String,
            positionMember: String, 
            description: String,
            image: String

        }
    });
</script>

<style>
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