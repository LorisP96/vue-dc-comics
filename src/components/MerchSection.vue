<template>
    <div class="merchs-container flex-evenly">
        <div class="merch-card">
            <div class="merch-img">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            </div>
            <a href="#"><h3>DIGITAL COMICS</h3></a> 
        </div>
        <div class="merch-card">
            <div class="merch-img">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
            </div>
            <a href="#"><h3>DC MERCHANDISE</h3></a> 
        </div>
        <div class="merch-card">
            <div class="merch-img">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            </div>
            <a href="#"><h3>SUBSCRIPTION</h3></a> 
        </div>
        <div class="merch-card">
            <div class="merch-img">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            </div>
            <a href="#"><h3>COMIC SHOP LOCATOR</h3></a> 
        </div>
        <div class="merch-card">
            <div class="merch-img">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            </div>
            <a href="#"><h3>DC POWER VISA</h3></a> 
        </div>
    </div>
</template>

<script>
export default {
  name: 'MerchSection',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';

.merchs-container {
    color: white;
    height: 150px;
    background-color: $brand-color;
    .merch-card {
        display: flex;
        align-items: center;

        .merch-img {
            width: 60px;
            padding: 0 10px;
        }
    }
}
</style>