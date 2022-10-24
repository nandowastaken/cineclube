<template>
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a href="#" class="navbar-item">
                    <h1 class="title is-3">Cineclube.</h1>
                </a>

                <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>

            <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-start">
                <a class="navbar-item" href="#">
                    Home
                </a>

                <a class="navbar-item" href="#about-us">
                    Quem somos?
                </a>

                <a class="navbar-item" href="#how-we-work">
                    Como funciona?
                </a>

                <a class="navbar-item" href="#next-meeting">
                    Próxima reunião
                </a>

                <a class="navbar-item" href="#movie">
                    Filme do mês
                </a>

                <a class="navbar-item" href="#team">
                    Equipe
                </a>
                
            </div>
        </div>
    </nav>
</template>

<script lang="ts">
    document.addEventListener('DOMContentLoaded', () => {
        // Get all "navbar-burger" elements
        const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);

        // Add a click event on each of them
        $navbarBurgers.forEach( el => {
            el.addEventListener('click', () => {

            // Get the target from the "data-target" attribute
            const target = el.dataset.target;
            const $target = document.getElementById(target);

            
            if ($target != null) {
                // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
                el.classList.toggle('is-active');
                $target.classList.toggle('is-active');
            }
            

        });
    });

});

    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'WebsiteNavbar',
        
});
</script>

<style>
    @import '../assets/styles/navbar.css';

</style>