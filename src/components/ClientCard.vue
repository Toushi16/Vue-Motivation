<template>

    <div class="container">

        <div class="client-wrapper">

            <img src="../assets/img/client-logo-05-primary.png">
            <img src="../assets/img/client-logo-06-primary.png">
            <img src="../assets/img/client-logo-07-primary.png">
            <img src="../assets/img/client-logo-04-primary.png">
            <img src="../assets/img/client-logo-03-primary.png">
            <img src="../assets/img/client-logo-02-primary.png">

        </div>

    </div>

</template>

<script>

    export default {
        
    }

</script>

<style lang="scss" scoped>

.container {
    max-width: 1024px;
    margin: 0 auto;
}

.client-wrapper {
    margin-top: 150px;
    margin-bottom: 150px;
    display: flex;
    gap: 80px;
    align-items: center;

    img {
        filter: grayscale(1);
        opacity: 0.6;
    }
}

</style>