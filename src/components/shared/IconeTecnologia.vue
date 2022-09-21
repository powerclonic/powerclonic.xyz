<template>
    <div class="efeito-neon botao-custom d-grid bg-cinza-25 rounded p-1 m-1">
        <img :src="imagem" alt="Tecnologia">
    </div>
</template>

<script setup>
defineProps({
    imagem: {
        required: true
    }
})
</script>

<style scoped>
.botao-custom {
    height: 4rem;
    place-content: center;
}

img {
    height: 3.5rem;
    width: 3.5rem;
}

</style>
