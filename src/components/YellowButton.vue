<template>
    <div class="column button-centralize" >
        <button class="button join-club">{{ message }}</button>
        
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'YellowButton',
        props: {
            message: String,
            
        }
    });
</script>

<style>
    .button-centralize {
        display: flex;
        justify-content: center;
        
    }

    .join-club {
        background-color: #FDE74C;
        color: black;
        border: none;
        border-radius: 20px;
        padding: 10px 70px;

        font-family: 'Inter', sans-serif;
        font-weight: 700;
        font-size: 24px;
    }

    @media only screen and (min-width: 1280px) {
        .join-club {
            background-color: #FD4C4C;
        }
    }
</style>