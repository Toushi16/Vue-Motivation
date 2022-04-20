<template>

    <div class="container">

        <div class="section-wrapper">

            <div class="book-store-text">

                <h3>BOOK STORE ONLINE</h3>
                <h1>Be Alpha With <span>Wingman's Book</span> </h1>
                <h4><img src="../assets/img/check-mark.png"> Help you understand yourself better</h4>
                <h4><img src="../assets/img/check-mark.png"> Revealing mature tips</h4>
                <h4><img src="../assets/img/check-mark.png"> Give the right advice</h4>
                <h4><img src="../assets/img/check-mark.png"> Fascinating examples of alpha man</h4>
                <button>Get Free Ebook</button>

            </div>

            <div class="card-wrapper">

                <div class="card">
                
                    <img src="../assets/img/product-book-11-400x400.jpg">
                    <h1>Alpha man by Maxcoach</h1>
                    <h2>$29.00</h2>

                </div>

                <div class="card">

                    <img src="../assets/img/product-book-10-400x400.jpg">
                    <h1>Real man 4.0 by Maxcoach</h1>
                    <h2>$39.00</h2>

                </div>

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
    max-width: 1024px;
    margin: 0 auto;
}

.section-wrapper {
    display: flex;
}

.book-store-text {
    margin-top: 100px;
    width: 40%;
 
    h3{
        font-family: $small-caps;
        margin-bottom: 60px;
        margin-top: 30px;
    }

    h1 {
        font-family: $elegant-title;
        font-weight: 400;
        color: $purple-text;
        font-size: 45px;

        span {
            color: $green-text;
        }
    }

    h4 {
        color: rgb(109, 109, 109);
        font-size: 18px;

        img {
            width: 18px;
            padding-right: 12px;
        }
    }

    button {
        cursor: pointer;
        border: none;
        color: white;
        margin-top: 30px;
        font-weight: 700;
        font-size: 16px;
        background-color: $green-text;
        padding: 20px 60px;
        border-radius: 10px;
    }
}

.card-wrapper {
    display: flex;
    margin-top: 120px;
    width: 40%;

    .card {
        text-align: center;
        
        img {
            width: 350px;
        }

        h1 {
            font-family: $small-caps;
            font-size: 20px;
            color: $purple-text;
        }

        h2 {
            font-family: $small-caps;
            font-size: 20px;
            color: $green-text;
        }
    }
}

</style>