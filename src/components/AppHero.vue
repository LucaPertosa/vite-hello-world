<script>
export default {
    name: "AppHero",
    data() {
        return {
            image: "../src/assets/img/01.png",
            altTxt: "Vite + Vue image"
        }
    }
}
</script>

<template>
    <img :src="image" :alt="altTxt">
</template>

<style>
img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}
</style>