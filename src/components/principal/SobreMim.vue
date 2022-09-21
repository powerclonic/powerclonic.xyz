<template>
    <section class="container-fluid py-3">
        <section class="row mb-3">
            <section class="col-12 col-lg-6 p-3 p-lg-0 pe-lg-2">
                <Sobre />
            </section>
            <section class="col-12 col-lg-6 p-3 p-lg-0 ps-lg-2">
                <RedesSociais />
            </section>
        </section>
        <section class="row mb-3">
            <section class="col-12 p-3 p-lg-0">
                <Projetos />
            </section>
        </section>
        <section class="row">
            <section class="col-12 col-lg-6 p-3 p-lg-0 pe-lg-2">
                <Contato />
            </section>
            <section class="col-12 col-lg-6 p-3 p-lg-0 ps-lg-2">
                <Conhecimentos />
            </section>
        </section>
    </section>
</template>

<script setup>
import { ref } from 'vue';
import RedesSociais from './sobre/RedesSociais.vue';
import Projetos from './sobre/Projetos.vue';
import Contato from './sobre/Contato.vue';
import Conhecimentos from './sobre/Conhecimentos.vue';
import Sobre from './sobre/Sobre.vue';


</script>

<style scoped>
#highlight {
    font-weight: bold;
    text-shadow: 0 0 2px #fff;
}
</style>
