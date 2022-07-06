<template>
  <header>
    <div class="flex-between">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="brand-logo">
        </div>
        <ul class="flex-evenly">
            <li v-for="link, index in menuList" :key="index" :class="{'current': link.current}">
                <a :href="link.url">
                    {{ link.text }}
                </a>
            </li>
        </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: 'PageHeader',
  data() {
    return {
        menuList: [
            {
                text: 'CHARACTERS',
                url: '#',
                current: false,
            },

            {
                text: 'COMICS',
                url: '#',
                current: true,
            },

            {
                text: 'MOVIES',
                url: '#',
                current: false,
            },

            {
                text: 'TV',
                url: '#',
                current: false,
            },

            {
                text: 'GAMES',
                url: '#',
                current: false,
            },

            {
                text: 'COLLECTIBLES',
                url: '#',
                current: false,
            },

            {
                text: 'VIDEOS',
                url: '#',
                current: false,
            },

            {
                text: 'FANS',
                url: '#',
                current: false,
            },

            {
                text: 'NEWS',
                url: '#',
                current: false,
            },

            {
                text: 'SHOP',
                url: '#',
                current: false,
            }
        ],
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';
header {
    height: 130px;
    .flex-between {
        width: 70%;
        height: 100%;
        margin: 0 auto;
        .logo > img {
            width: 80%;
            margin: 0 auto;
        }
        ul {
            width: 60%;
            height: 100%;
            li {
                text-align: center;
                height: 100%;
                line-height: 130px;
                a {
                    font-size: 13px;
                    font-weight: 700;
                }

                &.current {
                    border-bottom: 7px solid $brand-color;
                }
            }
        }
    }
}
</style>