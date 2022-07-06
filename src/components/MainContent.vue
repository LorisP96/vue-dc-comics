<template>
    <section>
        <div class="content-container">
            Content goes here
        </div>
    </section>
</template>

<script>
export default {
  name: 'MainContent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';
section {
    background-color: black;
    .content-container {
        color: white;
        height: 130px;
        width: 70%;
        margin: 0 auto;
    }
}
</style>