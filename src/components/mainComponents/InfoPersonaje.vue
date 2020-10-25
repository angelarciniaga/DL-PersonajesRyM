<template>
    <div class="fondo">
        <h1>Personajes de RyM</h1>
        <div v-for="(item, index) in datosRyM" :key="index">
            <img :src="item.image" :alt="item.name"> 
            <h2>{{item.name}}</h2>
        </div>

    </div>
</template>

<script>
export default {
    name: 'InfoPersonaje',
    props: {
        datosRyM: {
            type:Array,
            required: true
        }
    }

}
</script>

<style scoped>

.fondo {
    background-image: url('../../assets/cropped-RM_page-header_background1-3.png');
    background-size: cover;
    text-align: center;
}

img {
    width: 100px;
    border-radius: 50%;
}

h1 {
    color: rgb(5, 219, 5);
    font-family: Georgia, 'Times New Roman', Times, serif;
}

h2 {
    color: green !important; 
    font-size: 20px;
    font-weight: 700;
}
</style>