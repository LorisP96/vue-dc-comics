<template>
    <section>
        <div class="series-cont">
            <h4>CURRENT SERIES</h4>
        </div>
        
    </section>
</template>

<script>
export default {
  name: 'JumboBg',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';
section {
    width: 100%;
    height: 270px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    .series-cont {
        width: 70%;
        height: 100%;
        margin: 0 auto;
        position: relative;
        h4 {
            position: absolute;
            bottom: -17px;
            left: 0;
            color: white;
            background-color: $brand-color;
            display: inline-block;
            padding: 10px 15px;
        }
    }
}
</style>