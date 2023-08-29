<template>
<div class="hero-container">
    <h1 class="hero-text">COUNTY</h1>
    <div class="hero-img-container">
        <img class="hero-img" src="../assets/header1.png" alt="">
        <img class="hero-img" src="../assets/header2.png" alt="">
    </div>
</div>
</template>

<style scoped>

.hero-container {
    padding: 5%;
}

.hero-text {
    text-align: center;
    font-size: 25dvw;
    font-family: var(--font-family-secondary);
    color: var(--font-color-primary);
}

.hero-img-container {
    display: flex;
    width: 100%;
    justify-content: space-around;
}

.hero-img {
    filter: invert();
    width: 30dvw;
}

</style>

