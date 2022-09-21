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
                            descricao="Um bot do Discord feito com TypeScript usando a biblioteca Discord.js" />
                    </div>
                    <div class="col-12 col-xl-4 my-2 my-xl-0">
                        <CardProjeto :imagem="CredeasyBanner" titulo="CredEasy" repo="https://github.com/matheus-dresch/CredEasyV2"
                            descricao="Uma plataforma de crédito fictícia, feita utilizando PHP c/ Laravel e MySQL no backend e Vue 3 no frontend" />
                    </div>
                    <div class="col-12 col-xl-4 my-2 my-xl-0">
                        <CardProjeto :imagem="PowerclonicBanner" titulo="Este site"
                            repo="https://github.com/powerclonic/powerclonic.xyz"
                            descricao="Este site foi feito utilizando Vue 3 e Bootstrap 5.2" />
                    </div>
                </div>
            </article>
        </h6>
    </article>
</template>

<script setup>

import ArcanineBanner from '@/assets/images/projetos/arcaninebot.webp'
import CredeasyBanner from '@/assets/images/projetos/credeasy.webp'
import PowerclonicBanner from '@/assets/images/projetos/powerclonic.webp'
import CardProjeto from '../../shared/CardProjeto.vue';

</script>

<style>

</style>
