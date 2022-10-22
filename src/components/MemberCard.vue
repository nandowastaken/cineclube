<template>
    <div class="member">
            <div class="box-container">
                <img src="" alt="">
            </div>
            <div class="info-member">
                <div class="member-header">
                    <h1 class="member-name">{{ name }}</h1>
                    <p class="member-function">{{ positionMember }}</p>
                </div>
                        
                <p class="member-description">{{ description }}</p>
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
    }

    .member-name {
        color: white;
        font-family: "Inter", sans-serif;
        font-size: 22px;
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
        padding: 80px;
        border-radius: 20px;
        background-color: gray;
    }
</style>