<script>
export default {
    name: "AppJumbo",
    data() {
        return {
            title: "Benevenuto in VITE + VUE!"
        }
    }
}
</script>

<template>
    <h2>{{ title }}</h2>
    <img class="banner-img" src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="Milano">
</template>

<style>
    .banner-img {
        width: 100%;
        height: 300px;
        object-fit: contain;
    }
</style>