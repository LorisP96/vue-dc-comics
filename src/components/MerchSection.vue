<template>
    <section>
        <div class="merchs-container flex-evenly">
            <div class="merch-card">
                <div class="merch-img">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <a href="#"><h5>DIGITAL COMICS</h5></a> 
            </div>
            <div class="merch-card">
                <div class="merch-img">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <a href="#"><h5>DC MERCHANDISE</h5></a> 
            </div>
            <div class="merch-card">
                <div class="merch-img">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <a href="#"><h5>SUBSCRIPTION</h5></a> 
            </div>
            <div class="merch-card">
                <div class="merch-img resize">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <a href="#"><h5>COMIC SHOP LOCATOR</h5></a> 
            </div>
            <div class="merch-card">
                <div class="merch-img">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <a href="#"><h5>DC POWER VISA</h5></a> 
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'MerchSection',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';
section {
    background-color: $brand-color;
    .merchs-container {
        color: white;
        height: 150px;
        width: 70%;
        margin: 0 auto;
        .merch-card {
            display: flex;
            justify-content: center;
            align-items: center;

            .merch-img {
                width: 60px;
                padding: 12px;
            }
            .resize {
                padding: 16px;
            }
        }
    }
}
</style>