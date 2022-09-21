<template>
    <div :title="titulo" id="botao" class="d-grid bg-cinza-25 rounded p-1 m-1">
        <img :src="imagem" alt="Tecnologia">
    </div>
</template>

<script setup>
defineProps({
    imagem: {
        required: true
    },
    titulo: {
        type: String,
        required: true
    }
})
</script>

<style scoped>
#botao {
    height: 4rem;
    transition-property: box-shadow transform;
    transition-duration: .5s;
    place-content: center;
}

#botao:hover {
    background-color: var(--cinza-50) !important;
    transform: scale(1.15);

    box-shadow: 0 0 20px var(--vermelho), 0 0 5px var(--laranja);
}

img {
    height: 3.5rem;
    width: 3.5rem;
}

</style>
