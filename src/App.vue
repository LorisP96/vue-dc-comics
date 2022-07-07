<template>
  <div id="app">
    <PageHeader/>
    <JumboBg/>
    <main>
      <MainContent/>
      <MerchSection/>
    </main>

    <footer>
      <FooterTop/>
      <FooterBottom/>
    </footer>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import JumboBg from './components/JumboBg.vue';
import MainContent from './components/MainContent.vue';
import MerchSection from './components/MerchSection.vue';
import FooterTop from './components/FooterTop.vue';
import FooterBottom from './components/FooterBottom.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    MerchSection,
    FooterTop,
    FooterBottom,
    JumboBg
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
@import './style/variables.scss';
</style>
