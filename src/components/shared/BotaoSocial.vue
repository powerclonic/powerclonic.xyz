<template>
    <a :href="url" class="efeito-neon botao d-flex justify-content-between justify-content-lg-center justify-content-xl-between bg-cinza-25 rounded p-1 px-3">
        <img :src="imagem" alt="Social">
        <p class="text-light m-0 d-grid d-lg-none d-xl-grid">
            {{ titulo }}
        </p>
    </a>
</template>

<script setup>
import { ref } from 'vue';

defineProps({
    imagem: {
        required: true
    },
    url: {
        type: String,
        required: false
    },
    titulo: {
        type: String,
        required: true
    },
})

</script>

<style scoped>
.botao {
    height: 4rem;
    text-decoration: none;

    transition: all .5s;
}

p {
    place-content: center;
}
</style>
