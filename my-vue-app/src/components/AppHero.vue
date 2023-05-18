<script>
    // Codice JS
</script>

<template>
    <img src="../assets/astro.png" alt="astro-img">
</template>

<style scoped>

img {
    width: 250px;
    position: absolute;
    left: 0;
    top: 75%;
    animation: fly 5s linear infinite;
    animation-delay: 3s;
}

@keyframes fly {
    0% {
        top: 75%;
        left: 0%;
    }

    50% {
        top: 0px;
        left: 45%;
        transform: rotate(190deg);
    }

    100% {
        top: 80%;
        left: 100%;
        transform: rotate(360deg);
    }
}

</style>