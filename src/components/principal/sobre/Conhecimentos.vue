<template>
    <div class="bg-cinza-25 rounded p-3 h-100   ">
        <h2 class="text-center text-white">O que eu sei{{ tituloTecnologia }}</h2>
        <h6 class="text-center text-light">Algumas das tecnologias que eu uso e trabalho com atualmente</h6>
        <section class="container">
            <div class="row">
                <div class="col-4 p-0" title="PHP" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="php"/>
                </div>
                <div class="col-4 p-0" title="Laravel" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="laravel" />
                </div>
                <div class="col-4 p-0" title="MySQL" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="mysql"/>
                </div>
            </div>
            <div class="row">
                <div class="col-4 p-0" title="TypeScript" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="typescript" />
                </div>
                <div class="col-4 p-0" title="VueJS" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="vue" />
                </div>
                <div class="col-4 p-0" title="Docker" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="docker"/>
                </div>
            </div>
            <div class="row">
                <div class="col-4 p-0" title="HTML 5" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="html" />
                </div>
                <div class="col-4 p-0"  title="CSS 3" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="css" />
                </div>
                <div class="col-4 p-0" title="Bootstrap" @mouseenter="mudaTituloTecnologia" @mouseleave="tituloTecnologia = ''">
                    <IconeTecnologia :imagem="bootstrapIcon" />
                </div>
            </div>
        </section>
    </div>
</template>

<script setup>

import php from '@/assets/icons/tecnologias/php.svg';
import mysql from '@/assets/icons/tecnologias/mysql.svg';
import laravel from '@/assets/icons/tecnologias/laravel.svg';
import vue from '@/assets/icons/tecnologias/vue.svg';
import typescript from '@/assets/icons/tecnologias/typescript.svg';
import html from '@/assets/icons/tecnologias/html.svg';
import css from '@/assets/icons/tecnologias/css.svg';
import docker from '@/assets/icons/tecnologias/docker.svg';
import bootstrapIcon from '@/assets/icons/tecnologias/bootstrap.svg';
import { ref } from 'vue';
import IconeTecnologia from '../../shared/IconeTecnologia.vue';

const tituloTecnologia = ref('');

function mudaTituloTecnologia(e) {
    const titulo = e.target.title;

    tituloTecnologia.value = ': ' + titulo;
}

</script>

<style>

</style>
