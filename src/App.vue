<script>
import componentsNavbar from './components/componentsNavbar.vue';
import componentsContent from './components/componentsContent.vue';
import componentsMain from './components/componentsMain.vue';
import componentsFooter from './components/componentsFooter.vue';

export default {
  name: 'app',
  data() {
    return {

    }
  },
  components: {//inserire tutti gli import che voglio eseguire
    componentsNavbar,
    componentsContent,
    componentsMain,
    componentsFooter
  }
}
</script>

<template>
  <componentsNavbar />
  <componentsContent />
  <componentsMain />
  <componentsFooter />
</template>

<style></style>
