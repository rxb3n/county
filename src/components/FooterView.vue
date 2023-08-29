<template>
    <div class="footer-container">

        <div class="footer-section">
            <p class="section">Services</p>
            <p>Bookkeeping</p>
            <p>Auditing</p>
            <p>Payroll</p>
        </div>

        <div class="footer-section">
            <p class="section">Team</p>
            <p>Accountants</p>
            <p>Carreers</p>
            <p>Press</p>
        </div>

        <div class="footer-section">
            <p class="section">Contact</p>
            <p>Email</p>
            <p>Phone</p>
            <p>Location</p>
        </div>

    </div>

    <p class="copyright">© 2023 County Accounting Services</p>
</template>


<style scoped>
.footer-container {
    width: 50%;
    display: flex;
    justify-content: space-around;
    color: white;
    font-family: var(--font-family-primary);
}

.section {
    font-size: 1.25em;
    margin-bottom: 1%;
}

.copyright {
    width: 50%;
    font-family: var(--font-family-primary);
    color: white;
    text-align: start;
    margin-left: 5%;
    margin-top: 2%;
}

</style>