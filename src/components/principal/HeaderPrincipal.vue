<template>
    <div id="container" class="d-xl-flex justify-content-between">
        <article id="titulo" class="d-grid fs-0 p-3 p-lg-0">
            <span id="titulo-fonte">powerclonic</span>
        </article>
        <figure id="souma-figure" class="m-0 d-none d-xl-block">
            <img class="h-100" :src="SoumaBanner" alt="Souma Yukihira">
        </figure>
    </div>
    <div id="borda-neon" />
</template>

<script setup>
import SoumaBanner from "@/assets/images/souma.png";
</script>

<style scoped>
#souma-figure {
    height: 15rem;
}

#titulo {
    place-content: center;

    font-family: 'Raleway', sans-serif;
    color: #fff;
}

#borda-neon {
    width: 100%;
    height: 5px;
    background-image: linear-gradient(90deg, var(--vermelho-claro), var(--laranja));

    box-shadow: 0 0px 15px var(--vermelho);
}

.fs-0 {
    font-size: 3.5rem;
}

@media (min-width: 768px) {
    #titulo {
        text-align: center!important;
    }
}

@media (min-width: 992px) {
    #titulo {
        font-size: 5rem!important;
        text-align: center!important;
    }
}



</style>
