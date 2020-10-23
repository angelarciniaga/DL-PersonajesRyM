<template>
    <div>
        <div v-for="(item, index) in datosRyM" :key="index">
            <img :src="item.image" :alt="item.name"> <span>{{item.name}}</span>
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

<style>

</style>