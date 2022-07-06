<template>
    <div class="bg-comic">
        <div class="flex-between">
            <div class="footer-list">
                <ul>
                    <li><h2>DC COMICS</h2></li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
                <ul>
                    <li><h2>SHOP</h2></li>
                    <li>Characters</li><li>Characters</li>
                </ul>
                <ul>
                    <li><h2>DC</h2></li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
                <ul>
                    <li><h2>SITES</h2></li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                    <li>Characters</li>
                </ul>
            </div>
            <div class="dc-logo-big"></div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'FooterTop',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';

.bg-comic {
    color: $brand-grey;
    height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;

    .flex-between {
        width: 70%;
        margin: 0 auto;
        height: 100%;

        .dc-logo-big {
            width: 60%;
            height: 100%;
            background-image: url(../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
        }
        .footer-list {
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            width: 40%;
            height: 100%;
            padding: 20px 0;
            h2 {
                color: white;
                margin: 5px 0; 
            } 
        }
    }
}
</style>