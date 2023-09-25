<script>
import componentsNavbar from './components/componentsNavbar.vue';
import componentsContent from './components/componentsContent.vue';
import componentsMain from './components/componentsMain.vue';
import componentsFooter from './components/componentsFooter.vue';
import componentsJumbotron from './components/componentsJumbotron.vue';

export default {
  name: 'app',
  data() {
    return {

    }
  },
  components: {//inserire tutti gli import che voglio eseguire
    componentsNavbar,
    componentsJumbotron,
    componentsContent,
    componentsMain,
    componentsFooter
  }
}
</script>

<template>
  <componentsNavbar />
  <componentsJumbotron />
  <componentsContent />
  <componentsMain />
  <componentsFooter />
</template>

<style></style>
