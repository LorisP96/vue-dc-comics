<template>
    <div class="card">
        <img :src="cardComponents.thumb" alt="">
        <div class="card-name">{{ cardComponents.series }}</div>
    </div>
</template>

<script>
export default {
  name: 'CardContent',
  props: {
    cardComponents: Object
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';
.card {
    width: calc((100% / 6) - 10px);
    margin: 5px;
    img {
        width : 100%;
        aspect-ratio: 1/1;
        margin: 0 auto;
        object-fit: cover;
        object-position: top;
    }
    .card-name {
        font-size: 12px;
        margin-top: 10px;
        margin-bottom: 20px;
        text-transform: uppercase;
    }
}
</style>