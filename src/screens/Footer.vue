<template>
    <div class="columns">
        <div class="column">
            <div class="institute-info">
                <img src="../assets/logo-if.png" alt="Logo do Instituto Federal." class="logo-if">
                <p class="institute-name">Instituto Federal de Educação, Ciência e Tecnologia de Alagoas</p>
                <p class="location">Campus Maceió</p>
            </div>

            <div class="copyright">
                <p class="copyright-text">©2022 Cineclube</p>
                <p class="copyright-text">Todos os direitos reservados.</p>
            </div>
            
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'WebFooter',
        components: {

        }
    })
</script>

<style>
    .logo-if {
        width: 64px;
    }

    .institute-name, .location, .institute-info {
        font-family: 'Inter', sans-serif;
    }

    .institute-name {
        text-align: center;
    }

    .location {
        font-weight: 900;
    }
    .institute-info {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        margin: 30px;
    }

    .copyright {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .copyright-text {
        font-family: 'Inter', sans-serif;
        font-weight: 500;
    }

    
</style>