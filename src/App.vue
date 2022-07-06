<template>
  <div id="app">
    <PageHeader/>

    <main>
      <MainContent/>
      <MerchSection/>
    </main>

    <!-- <Footer/> -->
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import MainContent from './components/MainContent.vue';
import MerchSection from './components/MerchSection.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    MerchSection
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
@import './style/variables.scss';
</style>
