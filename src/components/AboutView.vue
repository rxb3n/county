<template>
    <div class="about-container">
        <p class="about-text">Introducing County Accounting Services, where mathematics meets entertainment! 
            Prepare to have your spreadsheets spin and your numbers dance!</p>

            <div class="about-btn-container">
                <button class="about-btn-alt">Learn More</button>
                <button class="about-btn">Get Started</button>
            </div>
    </div>
</template>


<style scoped>
.about-container {
    width: 100vw;
}

.about-text {
    color: var(--font-color-secondary);
    font-family: var(--font-family-primary);
    font-size: 3.5vw;
    text-align: center;
}

.about-btn-container {
    width: 100vw;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.about-btn-alt {
    border-radius: 50px;
    border: none;
    background-color: var(--font-color-secondary);
    padding: 2%;
    margin-bottom: 2%;
    font-size: 3.5vw;
    text-align: start;
    color: var(--background-color);
    width: 95%;
}

.about-btn {
    border-radius: 50px;
    border: 5px solid var(--font-color-secondary);
    background-color: var(--background-color);
    padding: 2%;
    font-size: 3.5vw;
    text-align: start;
    color: var(--font-color-secondary);
    width: 95%;
}

</style>