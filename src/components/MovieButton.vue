<template>
    <div class="column button-centralize" >
        <button class="button join-club">{{ message }}</button>
        
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'MovieButton',
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
        background-color: #d21f35;
        color: black;
        border: none;
        border-radius: 20px;
        padding: 10px 70px;

        font-family: 'Inter', sans-serif;
        font-weight: 700;
        font-size: 24px;

        transition: 0.6s ease-out;
    }

    .join-club:hover {
        background-color: white;
        color: #d21f35;

    }

    @media only screen and (min-width: 1280px) {
        .join-club {
            padding: 10px 50px;
            border-radius: 40px;
        }
    }
</style>