<template>
    <section>
        <div class="footer-bottom flex-between">
            <div class="button">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="social">
                <span>FOLLOW US</span>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'FooterBottom',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';
section {
    background-color: $bg-main-color;
    .footer-bottom {
        color: $brand-grey;
        height: 130px;
        width: 70%;
        margin: 0 auto;
        .button {
            display: flex;
            justify-content: center;
            align-items: center;

            button {
                border: 2px solid $brand-color;
                background-color: $bg-main-color;
                color: white;
                padding: 15px;
            }
        }
        .social {
            width: 40%;
            display: flex;
            align-items: center;
            span {
                color: $brand-color;
                font-weight: 700;
                min-width: 100px;
                margin-right: 20px;
            }
            img {
                padding: 10px;
                width: 55px;
            }
        }
    }
}
</style>