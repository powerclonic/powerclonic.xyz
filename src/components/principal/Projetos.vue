<template>
    <article class="bg-cinza-25 rounded p-3 h-100">
        <h2 class="text-center text-white">Projetos</h2>
        <h6 class="text-center text-light">
            Para ver meus outros projetos acesse meu
            <a href="https://github.com/powerclonic" class="text-white">GitHub</a>
            :)
            <article class="d-grid">
                <div class="row mt-4">
                    <div class="col-12 col-xl-4 my-2 my-xl-0">
                        <CardProjeto :imagem="ArcanineBanner" titulo="Arca9 Bot"
                            descricao="Um bot do Discord simples feito com TypeScript" />
                    </div>
                    <div class="col-12 col-xl-4 my-2 my-xl-0">
                        <CardProjeto :imagem="CredeasyBanner" titulo="CredEasy"
                            descricao="Uma plataforma de crédito fictícia, feita utilizando PHP c/ Laravel e MySQL no backend e Vue 3 no frontend" />
                    </div>
                    <div class="col-12 col-xl-4 my-2 my-xl-0">
                        <CardProjeto :imagem="PowerclonicBanner" titulo="Este site"
                            descricao="Este site foi feito utilizando Vue 3" />
                    </div>
                </div>
            </article>
        </h6>
    </article>
</template>

<script setup>
import CardProjeto from './CardProjeto.vue';

import ArcanineBanner from '@/assets/images/projetos/arcaninebot.webp'
import CredeasyBanner from '@/assets/images/projetos/credeasy.webp'
import PowerclonicBanner from '@/assets/images/projetos/powerclonic.webp'

</script>

<style>

</style>
