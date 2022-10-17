<template>
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a href="#" class="navbar-item">
                    <h1>Cineclube.</h1>
                </a>

                <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>

            <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-start">
                <a class="navbar-item">
                    Home
                </a>

                <a class="navbar-item">
                    Quem somos?
                </a>

                <a class="navbar-item">
                    Como funciona?
                </a>

                <a class="navbar-item">
                    Próxima reunião
                </a>

                <a class="navbar-item">
                    Filme do mês
                </a>

                <a class="navbar-item">
                    Participe
                </a>

                <a class="navbar-item">
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
    name: 'WebsiteNavbar'
});
</script>

<style>
    .navbar {
        width: 100%;
        position: absolute;
        background-color: transparent;
    }

</style>