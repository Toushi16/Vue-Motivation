<template>

    <header>

        <div class="header-wrapper container">
            
            <img class="header__logo" src="../assets/img/dark-logo.png" alt="">

            <nav class="header__nav">

                <ul>
                    <li v-for="(links, i) in navItems" :key="i">
                        {{links}}
                    </li>
                </ul>

            </nav>

            <div class="header__social-icons">

                <ul>
                    <li v-for="(icon, i) in socialIcons" :key="i">
                        <img :src="icon.img">
                    </li>
                </ul>

            </div>

        </div>

        <div class="header-content-wrapper container">
            
            <div class="content__txt">

                <h3>I'M WINGMAN</h3>
                <h1>Peace On Earth A Wonderful Wish But No Way</h1>
                <h5>Success isn't overnight. It's when everyday you get a little better than the day before. It all adds up.</h5>
                <button><a href="#">Get Started For Free <span><img src="../assets/icons/arrow-right-solid.svg" width="10"></span></a></button>
            
            </div>
                
            <div class="content__img">
                
                <img src="../assets/img/home-movation-hero-image.png" alt="">

            </div>

        </div>

    </header>

</template>

<script>

    export default {

       data() {
           return {

               navItems: [
                   'Home',
                   'Pages',
                   'Courses',
                   'Features',
                   'Blog',
                   'Shop'
               ],

               socialIcons: [
                    {img: require (`../assets/icons/twitter-brands.svg`)},
                    {img: require (`../assets/icons/facebook-f-brands.svg`)},
                    {img: require (`../assets/icons/instagram-brands.svg`)},
                    {img: require (`../assets/icons/linkedin-brands.svg`)}
               ],

           }
       }, 
    }

</script>

<style lang="scss" scoped>

@import '../assets/scss/mixin.scss';

.container {
    max-width: 1024px;
    margin: 0 auto;
}

header {
    background-image: url('../assets/img/background-pattern-wavify.png');
    background-position: cover;
    background-color: $bg-hero;

.header-wrapper {
    display: flex;
    min-height: 40px;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 100px;

    .header__logo {
        margin-top: 20px;
        height: 30px;
        cursor: pointer;
    }

    li{
        display: inline;
        padding-left: 30px;
        font-size: 15px;
        color: $nav-text;
        cursor: pointer;
    }

    .header__social-icons {

        img {
            width: 18px;
            opacity: 0.7;
            cursor: pointer;
        }

    } 
}

.header-content-wrapper{
    display: flex;
    

    .content__txt{
        display: flex;
        flex-direction: column;
        width: 50%;

        h3 {
            font-family: $small-caps;
            color:$bold-text;
        }

        h1 {
            font-family: $elegant-title;
            color: $dark-text;
            font-size: 60px;
        }

        h5 {
            margin-top: 50px;
            font-family: $normal-text;
            color: $grey-text;
            font-size: 18px;
        }

        button {
            margin-top: 50px;
            background-color: $green-text;
            border: none;
            width: 300px;
            height: 70px;
            border-radius: 10px;

            a {
                text-decoration: none;
                color: white;
                font-weight: bold;
                font-size: 18px;
                
                img {
                    margin: -2px 10px;
                    width: 15px;
                    filter: brightness(0) invert(1);
                }
            }
        }
    }

    .content__img {
        width: 50%;

        img {
            background-image: url('../assets/img/home-movation-shape-face.png');
            background-repeat: no-repeat;
            background-size: 100%;
            background-position: bottom;
        }
    }
}
}

</style>