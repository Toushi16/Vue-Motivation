<template>
    <div class="container">

        <section>

            <div class="rating-wrapper">

                <div class="rating__box">

                    <h2>1.926</h2>
                    <h3>FINISHED SESSIONS</h3>
                
                </div>

                <div class="rating__box">

                    <h2>100%</h2>
                    <h3>SATISFACTION RATE</h3>
                
                </div>

                <div class="rating__box">

                    <h2>3092+</h2>
                    <h3>ENROLLED LEARNERS</h3>
                
                </div>

                <div class="rating__box">

                    <h2>200</h2>
                    <h3>ONLINE INSTRUCTORS</h3>
                
                </div>

            </div>

            <div class="alpha-section">

                <div class="alpha-txt">
                    
                    <h3>ABOUT ME</h3>
                    <h1>How to Be an Alpha Male: The 15 Habits of True Alphas</h1>
                
                </div>
                
                <div class="alpha-descriptions">

                    <h3>Want to learn how to be <span>an alpha male</span>? How to be more masculine? How to be the man you've always wanted to be?</h3>
                    <h4>Your goal to show the consistency of business, core values, and customer care.Punctuality, responsibility, individuality, accuracy, enthusiasm - you have to clearly explain how these qualities are applicable to your work. And the important thing is you do love what you do.</h4>

                </div>
            
            </div>

            <div class="video-section container">

                <div class="video-img">
                    <img src="../assets/img/home-movation-video-poster-670x450.jpg" alt="">
                    <img class="youtube-btn" src="../assets/img/icon-youtube-play.png">
                </div>

                <div class="video__txt">
                    <h1>"Every morning you have two choices: continue to sleep with your dreams, or wake up and chase them."</h1>
                    <h2>Kaixa Stark</h2>
                    <h3>WINGMAN</h3>
                </div>

            </div>

        </section>

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

.rating-wrapper {
    padding-top: 70px;
    display: flex;
    gap: 80px;
    justify-content: center;

    .rating__box {
        background-image: url('../assets/img/background-pattern-grid-line-06.png');
        
        h2 {
            text-align: center;
            font-size: 40px;
            font-family: $small-caps;
            color:$green-text;
            height: 40px;
            margin-bottom: 10px;
        }

        h3 {
            text-align: center;
            font-size: 16px;
            font-family: $small-caps;
            color:$bold-text;
            width: 200px;
        }
    }
}

.alpha-section {
    margin-top: 100px;
    display: flex;
    justify-content: space-between;

    .alpha-txt {
        width: 30%;

        h3 {
            font-family: $small-caps;
            color: $green-text;
            margin-bottom: 30px;
        }

        h1 {
            width: 420px;
            font-family: $elegant-title;
            color: $dark-text;
            font-size: 40px;
            letter-spacing: 1px;
        }
    }

    .alpha-descriptions {
        width: 50%;
        margin-top: 60px;

        h3 {
            font-family: $small-caps;
            font-size: 18px;
            width: 650px;

            span {
                color: $green-text;
            }
        }

        h4 {
            margin-top: 20px;
            font-family: $small-caps;
            color: #918A96;
        }
    }
}

.video-section {
    margin-top: 100px;
    display: flex;

    .video-img {
        position: relative;
        width: 60%;

        img {
            width: 100%; 
        }

        .youtube-btn {
            position: absolute;
            width: 100px;
            left: 41%;
            top: 40%;
            cursor: pointer;

        }
    }

    .video__txt {
        width: 35%;
        font-family: $elegant-title;
        color: $purple-text;
        margin-left: 80px;
    }
}

</style>