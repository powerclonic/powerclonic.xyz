<template>
    <div id="borda-neon" />
    <article id="titulo" class="d-grid fs-5 p-2">
        <span id="titulo-fonte">powerclonic - 2022</span>
    </article>
</template>

<script setup>

</script>

<style scoped>
#borda-neon {
    width: 100%;
    height: 5px;
    background-image: linear-gradient(90deg, var(--laranja), var(--vermelho-claro));

    box-shadow: 0 0px 15px var(--vermelho);
}

#titulo {
    place-content: center;

    font-family: 'Raleway', sans-serif;
    color: #fff;
}
</style>
