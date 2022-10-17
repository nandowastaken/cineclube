<template>
    <div class="column button-centralize" >
        <button class="button join-club">Junte-se ao Clube</button>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'YellowButton'
    });
</script>

<style>
    .button-centralize {
        display: flex;
        justify-content: center;
    }

    .join-club {
        background-color: #FDE74C;
        border: none;
        border-radius: 20px;
        padding: 10px 70px;

        font-family: 'Inter', sans-serif;
        font-weight: 700;
        font-size: 24px;
    }
</style>