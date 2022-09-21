<template>
    <div class="bg-cinza-25 rounded p-3 h-100">
        <h2 class="text-center text-white">Contato</h2>
        <h6 class="text-center text-light">Você pode me chamar em qualquer lugar, inclusive nas redes que falei lá em cima</h6>
        <section class="container">
            <div class="row">
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="EmailIcon" url="mailto:matheus.dresch02@gmail.com" titulo="E-mail" />
                </div>
                <div class="col-12 col-md-6 p-1">
                    <BotaoSocial :imagem="LinkedinIcon" url="https://www.linkedin.com/in/matheus-dresch/"
                        titulo="LinkedIn" />
                </div>
            </div>
        </section>
    </div>
</template>

<script setup>

import EmailIcon from '@/assets/icons/sociais/email.svg';
import LinkedinIcon from '@/assets/icons/sociais/linkedin.svg';
import BotaoSocial from '../../shared/BotaoSocial.vue';

</script>

<style>
</style>
