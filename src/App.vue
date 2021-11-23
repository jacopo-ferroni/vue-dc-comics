<template>
  <div id="app">
    <Header />
    <Content />
    <Info />
    <Footer />
    <Sign />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Info from '@/components/Info.vue';
import Footer from '@/components/Footer.vue';
import Sign from '@/components/Sign.vue';

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Info,
    Footer,
    Sign,
  }
}
</script>

<style lang="scss">
* {
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
  font-family: sans-serif;
}
</style>
