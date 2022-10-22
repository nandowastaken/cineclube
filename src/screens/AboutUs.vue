<template>
    <div class="columns about-us">
        <div class="column">
            <div class="content-about">
                <h1 class="section-title" id="about-us">Quem somos?</h1>
                <p class="description">
                    Nós somos o Cineclube, o clube oficial de cinema do IFAL! Nós fomos fundados na pandemia pela aluna Talita Raquel, onde fizemos inúmeros encontros virtuais, e agora continuamos presencialmente o clube sob a liderança do aluno Fernando Jorge, uma vez que a líder se formou.
                </p>
            </div>
            
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'AboutUs',
        components: {

        }
    })
</script>
    
<style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
    .about-us {
        background: black;
    }

    .content-about {
        display: flex;
        flex-direction: column;
        gap: 10px;
        margin: 10px;
    }

    .section-title, .description {
        font-family: 'Inter', sans-serif;
        color: white;
    }

    .section-title {
        font-size: 30px;
        font-weight: 700;
        
    }

    .description {
        font-size: 20px;
        font-weight: 400;

    }
</style>