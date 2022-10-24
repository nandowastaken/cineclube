<template>
    <div class="columns">
        <div class="column">
            <div class="institute-info">
                <img src="../assets/logos/logo-if.png" alt="Logo do Instituto Federal." class="logo-if">
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
    
    @import '../assets/styles/footer.css';
    
</style>