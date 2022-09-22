<template>
    <grid>
        <img v-bind:src="url" :alt="nombre">
        <h3>{{ nombre }}</h3>
        <p>{{ descripcion}}</p>
        <h4>{{ precio }}</h4>
    </grid>
</template>

<script>
import Grid from "./Grid.vue";
    export default {
    props: {
        url: { String, },
        nombre: { String, },
        descripcion: { String, },
        precio: { String, },
    },
    components: { Grid }
};
</script>

<style scoped>
    img {
        width: 10rem;
        height: 15rem;
        padding: 0.5rem;
        background-color: snow;

    }
    h4 {
        color:red;
    }

</style>