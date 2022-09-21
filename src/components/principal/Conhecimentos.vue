<template>
    <div class="bg-cinza-25 rounded p-3 h-100   ">
        <h2 class="text-center text-white">O que eu sei</h2>
        <h6 class="text-center text-light">Algumas das tecnologias que eu uso e trabalho com atualmente</h6>
        <section class="container">
            <div class="row">
                <div class="col-4">
                    <IconeTecnologia :imagem="php" titulo="PHP"/>
                </div>
                <div class="col-4">
                    <IconeTecnologia :imagem="laravel" titulo="Laravel" />
                </div>
                <div class="col-4">
                    <IconeTecnologia :imagem="mysql" titulo="MySQL"/>
                </div>
            </div>
            <div class="row">
                <div class="col-4">
                    <IconeTecnologia :imagem="typescript" titulo="TypeScript" />
                </div>
                <div class="col-4">
                    <IconeTecnologia :imagem="vue" titulo="VueJS" />
                </div>
                <div class="col-4">
                    <IconeTecnologia :imagem="docker" titulo="Docker" />
                </div>
            </div>
            <div class="row">
                <div class="col-4">
                    <IconeTecnologia :imagem="html" titulo="HTML" />
                </div>
                <div class="col-4">
                    <IconeTecnologia :imagem="css" titulo="CSS" />
                </div>
                <div class="col-4">
                    <IconeTecnologia :imagem="bootstrapIcon" titulo="Bootstrap" />
                </div>
            </div>
        </section>
    </div>
</template>

<script setup>
import IconeTecnologia from './IconeTecnologia.vue';

import php from '@/assets/icons/tecnologias/php.svg';
import mysql from '@/assets/icons/tecnologias/mysql.svg';
import laravel from '@/assets/icons/tecnologias/laravel.svg';
import vue from '@/assets/icons/tecnologias/vue.svg';
import typescript from '@/assets/icons/tecnologias/typescript.svg';
import html from '@/assets/icons/tecnologias/html.svg';
import css from '@/assets/icons/tecnologias/css.svg';
import docker from '@/assets/icons/tecnologias/docker.svg';
import bootstrapIcon from '@/assets/icons/tecnologias/bootstrap.svg';

</script>

<style>

</style>
