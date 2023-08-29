<template>
    <div class="cta-container">

        <div class="cta-text">
            <p class="text">JOIN TODAY</p>
        </div>

        <div class="cta-form">
            <input type="text" placeholder="name@email.com">
            <p class="button">Subscribe</p>
        </div>

    </div>
</template>

<style scoped>

p {
    margin: 0;
    padding: 0;
}
.cta-container {
    padding: 0;
    width: 100%;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding-top: 4%; padding-bottom: 4%;
}

.text {
    width: 95vw;
    font-family: var(--font-family-secondary);
    color: var(--font-color-secondary);
    font-size: 20vw;
    text-align: center;
}

.cta-form {
    display: flex;
    flex-direction: column;
    width: 90%;
    font-family: var(--font-family-primary);
}

.cta-form input {
    margin-bottom: 2%;
    padding: 5%;
    border-radius: 50px;
    font-size: 2.5vw;
    border:5px solid var(--button-secondary);
    background-color: var(--background-color);
    color: white;
}

.cta-form input::placeholder {
    color: white;
}

.cta-form .button {
    margin-bottom: 2%;
    padding: 5%;
    border-radius: 50px;
    font-size: 2.5vw;
    border:5px solid var(--background-color);
    background-color: var(--button-secondary);
    color: var(--background-color);
}

</style>