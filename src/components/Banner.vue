<template>
    <div class="banner-wrapper">
        <div class="description">
            <h3>Debit that builds credit.</h3>
            <p>Extra is the first debit card that helps build credit and earns rewards points. No credit checks. Use your bank.</p>
            <button>Apply Rn!</button>
            <summary>5 stars, very nice. Trusted by 200,000+ Customers</summary>
        </div>
        <div>
            <img src="../assets/extra_uwu.png" />
        </div>
    </div>
</template>

<script>

    export default {
        name: 'Banner'
    }

</script>

<style scoped>

    .banner-wrapper {
        display: flex;
        flex-direction: row;
        margin-top: 5%;
        align-content: center;
        justify-content: center;
    }

    .description {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    h3 {
        font-size: 40px;

    }

    button {
        max-width: 25%;
        margin-bottom: 10px;
    }

    summary {
        color: #cdcdcd ;
    }

</style>