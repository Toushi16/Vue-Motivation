<template>

    <div class="container">

        <div class="carousel-wrapper">

            <div class="carousel-text">

                <h2>REAL STORIES</h2>
                <h3>I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.</h3>
                <img src="../assets/img/testimonial-avata-02.jpg">
                <h4>Mina Hollace</h4>
                <h5>/Freelancer</h5>

            </div>

            <div class="carousel-img">
            </div>

        </div>

    </div>

</template>

<script>

    export default {
        
    }

</script>

<style lang="scss" scoped>

@import '../assets/scss/mixin.scss';

.container {
    background-color: $bg-hero;
}

.carousel-wrapper {
    display: flex;

    .carousel-text {
        background-image: url('../assets/img/background-pattern-wavify.png');
        width: 55%;
        text-align: center;

        h2 {
            margin-top: 100px;
            color: $green-text;
            font-family: $small-caps;
            font-size: 16px;
        }

        h3 {
            margin-top: 50px;
            width: 400px;
            margin-left: 270px;
            font-family: $small-caps;
            font-weight: 400;
            }

        img {
            margin-top: 30px;
            border-radius: 100px;
            width: 80px;
        }

        h4 {
            font-family: $small-caps;
            font-size: 15px;
        }

        h5 {
            font-family: $small-caps;
            color: $grey-text;
            margin-bottom: 100px;
        }
    }

    .carousel-img {
        width: 50%;
        background-image: url('../assets/img/home-movation-testimonial-image-768x562.jpg');
        background-repeat: no-repeat;
        background-size: cover;    
    }
}

</style>