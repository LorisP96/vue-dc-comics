<template>
  <div id="app">
    <PageHeader/>

    <main>
      <MainContent/>
      <MerchSection/>
    </main>

    <footer>
      <FooterTop/>
    </footer>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import MainContent from './components/MainContent.vue';
import MerchSection from './components/MerchSection.vue';
import FooterTop from './components/FooterTop.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    MerchSection,
    FooterTop
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
@import './style/variables.scss';
</style>
