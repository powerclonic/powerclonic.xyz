<template>
    <div class="card-projeto efeito-neon d-flex justify-content-between flex-column h-100 bg-cinza-25 rounded p-3">
        <figure class="imagem m-0">
            <img :src="imagem" alt="Banner projeto" class="w-100 rounded">
        </figure>
        <h3 class="m-2" >{{ titulo }}</h3>
        <p class="px-3">{{ descricao }}</p>

        <a v-if="repo" class="btn btn-secondary" :href="repo">Repositório no GitHub</a>
        <a v-else class="btn btn-secondary disabled" :href="repo">Repositório no GitHub</a>
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
    },
    descricao: {
        type: String,
        required: true
    },
    repo: {
        type: String,
        required: false
    }
})

</script>

<style scoped>
.card-projeto {
    height: 10rem;
    transition-property: box-shadow transform;
    transition-duration: .5s;

    height: fit-content;
}

.imagem {
    width: 100%;
    height: fit-content;
}

.imagem > img {
    box-shadow: 0 0 15px 0px #fff5;
}
</style>
