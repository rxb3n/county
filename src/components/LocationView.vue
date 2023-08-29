<template>
    <div class="location-container">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7945.693367475547!2d-3.9803249341042095!3d5.286606678677817!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xfc1eeba32bfbf1b%3A0xa1f41688cd35698f!2sZone%204C%2C%20Abidjan%2C%20C%C3%B4te%20d&#39;Ivoire!5e0!3m2!1sfr!2sfr!4v1693323761879!5m2!1sfr!2sfr" 
        style="border:0;" 
        allowfullscreen="true" 
        loading="lazy" 
        referrerpolicy="no-referrer-when-downgrade"></iframe>

        <div class="location-image">
            <img src="../assets/banner1.webp" alt="">
        </div>
    </div>

</template>

<style scoped>

.location-container {
    display: flex;
    flex-direction: column;
    padding-top: 2%;
    width: 100%;
    align-items: center;
    margin: auto;
}

.location-container iframe {
    width: 90%;
    height: 50dvh;
    border-radius: 18px;
    filter: sepia(100%) hue-rotate(180deg) brightness(80%);
    padding-bottom: 1%;

}

.location-image {
    width: 100%;
}

.location-image img {
    width: 90%;
    height: 50dvh;
    display: flex;
    flex-direction: column;
    filter: sepia(100%) hue-rotate(180deg) brightness(80%);
    margin-left: 5%;
}
</style>