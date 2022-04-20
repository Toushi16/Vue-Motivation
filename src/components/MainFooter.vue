<template>

    <footer>

        <div class="container">

            <div class="footer-wrapper">

                <div class="info-footer">

                    <h2>Address</h2>
                    <h3>382 NE 191st ST # 87394 Miami, FL 33179-3899</h3>
                    <h3>+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)</h3>
                    <h3>support@maxcoach.com</h3>
                    <img class="fb-icon" src="../assets/icons/facebook-f-brands.svg">
                    <img src="../assets/icons/twitter-brands.svg">
                    <img src="../assets/icons/instagram-brands.svg">
                    <img src="../assets/icons/linkedin-brands.svg">

                </div>

                <div>

                </div>

            </div>

        </div>

    </footer>

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

footer {
    background-color: $footer-bg;
    width: 100%;
    height: 400px;
}

.footer-wrapper{
    display: flex;

    .info-footer {
        width: 50%;
    
        h2 {
            margin-top: 80px;
            color: white;
            font-family: $small-caps;
            font-size: 18px;
        }

        h3 {
            color: grey;
            font-family: $small-caps;
            font-size: 14px;
            margin-top: 20px;
            margin-bottom: 20px;
        }

        .fb-icon {
                width: 16px;
            }

        img {
            margin-top: 20px;
            width: 23px;
            margin-right: 30px;
        }
    }
}

</style>