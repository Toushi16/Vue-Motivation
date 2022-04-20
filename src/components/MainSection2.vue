<template>

    <div class="container">

        <div class="title-online-courses">

            <h2>BEGIN YOUR JOURNEY AT MAXCOACH</h2>
            <h1>Latest <span>Online Courses</span> </h1>
        
        </div>

        <br>
        <br>

        <div class="cards-wrapper">

            <div class="card">

                <img src="../assets/img/motivation-course-06-480x298.jpg">
                <h1>$30.00</h1>
                <h2>How to be Successful: Create A Growth Mindset For Success</h2>
                <h3> <img class="paper-icon" src="../assets/img/paper-write.png"> 3 Lessons <img class="people-icon" src="../assets/img/people-icon.png" alt=""> 50 Students</h3>
            
            </div>

            <div class="card">

                <img src="../assets/img/motivation-course-05-480x298.jpg">
                <h1>$30.00</h1>
                <h2>How to Build Confidence in Your Abilities</h2>
                <h3> <img class="paper-icon" src="../assets/img/paper-write.png"> 1 Lessons <img class="people-icon" src="../assets/img/people-icon.png" alt=""> 50 Students</h3>
            
            </div>

            <div class="card">

                <img src="../assets/img/motivation-course-04-480x298.jpg">
                <h1>$20.00</h1>
                <h2>Productivity Machine - Focus in a Distracted World</h2>
                <h3> <img class="paper-icon" src="../assets/img/paper-write.png"> 5 Lessons <img class="people-icon" src="../assets/img/people-icon.png" alt=""> 50 Students</h3>
            
            </div>   

            <div class="card">

                <img src="../assets/img/motivation-course-03-480x298.jpg">
                <h1>$20.00</h1>
                <h2>Effective Time Management Mastery - Complete Guide</h2>
                <h3> <img class="paper-icon" src="../assets/img/paper-write.png"> 18 Lessons <img class="people-icon" src="../assets/img/people-icon.png" alt=""> 50 Students</h3>
            
            </div>

            <div class="card">

                <img src="../assets/img/motivation-course-02-480x298.jpg">
                <h1>$25.99</h1>
                <h2>Body Language Secrets for Entrepreneurs</h2>
                <h3> <img class="paper-icon" src="../assets/img/paper-write.png"> 19 Lessons <img class="people-icon" src="../assets/img/people-icon.png" alt=""> 50 Students</h3>
            
            </div>

            <div class="card">

                <img src="../assets/img/motivation-course-01-480x298.jpg">
                <h1>$19.99</h1>
                <h2>Management Skills: The Science of Leadership</h2>
                <h3> <img class="paper-icon" src="../assets/img/paper-write.png"> 17 Lessons <img class="people-icon" src="../assets/img/people-icon.png" alt=""> 50 Students</h3>
            
            </div>

            <button>View all courses <img src="../assets/icons/arrow-right-solid.svg"></button>            

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

.title-online-courses {
    margin-top: 150px;
    margin-bottom: 50px;
    text-align: center;

    h2 {
        color: $grey-text;
        font-family: $small-caps;
        font-size: 18px;
        margin-bottom: 25px;
    }

    h1 {
        font-family: $elegant-title;
        font-size: 40px;
        padding-left: 20px;
        color: $purple-text;
        
        span {
            color: $green-text;
        }
    }
}

.cards-wrapper {
    display: flex;
    flex-wrap: wrap;

    .card {
        width: 33.33%;

        img {
            width: 95%;
            border-radius: 10px;
        }

        h1 {
            color: $green-text;
            font-family: $small-caps;
            font-size: 25px;
        }

        h2 {
            color: $purple-text;
            font-family: $small-caps;
            font-size: 20px;
        }

        h3 {
            color: grey;
            font-family: $small-caps;
            font-size: 18px;
            margin-bottom: 60px;

            .paper-icon {
            width: 15px;
            border-radius: 0;
        }

        .people-icon {
            width: 23px;
            
        }

        }
    }
}

button {
    display: flex;
    gap: 10px;
    margin-left: 35%;
    padding: 20px 60px;
    border-radius: 10px;
    border: none;
    background-color: $green-text;
    color: white;
    font-weight: 700;
    font-size: 18px;
    cursor: pointer;

    img {
        width: 18px;
        filter: brightness(0) invert(1);
    }
}

</style>