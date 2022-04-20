<template>

    <div class="container">

        <div class="blog-text">

            <h2>BLOG UPDATED</h2>
            <h1>Interesting <span>articles updated</span> daily</h1>

        </div>

        <div class="blogs-wrapper">

            <div class="blog-card">

                <img src="../assets/img/motivation-blog-04-480x325.jpg">
                <h3> <img class="calendar-icon" src="../assets/img/calendar-icon.png"> May 13, 2020 </h3>
                <h1>How to Stay True to Your Personal Brand</h1>
                <h4>When it comes to your business or career, you want ...</h4>

            </div>

            <div class="blog-card">

                <img src="../assets/img/motivation-blog-03-480x325.jpg">
                <h3> <img class="calendar-icon" src="../assets/img/calendar-icon.png"> May 13, 2020 </h3>
                <h1>5 Vital Lessons in 5 Years of Freelancing </h1>
                <h4>Being self-employed and working from home, it's easy to get ...</h4>

            </div>

            <div class="blog-card">

                <img src="../assets/img/motivation-blog-02-480x325.jpg">
                <h3> <img class="calendar-icon" src="../assets/img/calendar-icon.png"> May 13, 2020 </h3>
                <h1>11 Super Useful Tips for Small-Business Owners</h1>
                <h4>Being a small-business owner poses a ton of challenges. We ...</h4>

            </div>

            <div class="blog-card">

                <img src="../assets/img/motivation-blog-01-480x325.jpg">
                <h3> <img class="calendar-icon" src="../assets/img/calendar-icon.png"> May 13, 2020 </h3>
                <h1>How to Give Yourself Grace to Start Again</h1>
                <h4>Forgive yourself for bad habits you may have started or ...</h4>

            </div>

        </div>

        <h3 class="posts-btn"><a href="#">VIEW ALL POSTS</a></h3>

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

.blog-text {
    margin-top: 200px;
    
    h2 {
        font-family: $small-caps;
        font-size: 18px;
    }

    h1 {
        font-family: $elegant-title;
        font-weight: 400;
        font-size: 38px;
        margin-bottom: 100px;
        margin-top: 30px;

        span {
            color: $green-text;
        }
    }
}

.blogs-wrapper {
    display: flex;
    gap: 30px;
    

    .blog-card {
        
        img {
            width: 100%;
        }

        h3 {
            margin-top: 30px;
            margin-bottom: 20px;
            font-family: $small-caps;
            
            .calendar-icon {
                width: 7%;
            }
        }

        h1 {
            font-family: $small-caps;
            font-size: 19px;
            margin-bottom: 20px;
        }

        h4 {
            color: rgb(117, 117, 117);
            font-family: $small-caps;
            font-size: 14px;
            font-weight: 400;
        }
    }
}

.posts-btn {
    margin-top: 40px;
    width: 150px;
    margin-left: 440px;
    font-family: $small-caps;
    border-bottom: 2px solid $green-text;
    margin-bottom: 200px;

        a {
            color: $green-text;
            text-decoration: none;
        }

}

</style>