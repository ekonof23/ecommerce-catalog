<template>
  <div id="app">
    <div v-if="category === 'Men'">
      <MenSection />
    </div>
    <div v-else-if="category === 'Women'">
      <WomenSection />
    </div>
    <div v-else>
      <UnavailableProduct />
    </div>
  </div>
</template>

<script>
import MenSection from './components/MenSection.vue'
import WomenSection from './components/WomenSection.vue'
import UnavailableProduct from './components/UnavailableProduct.vue'

export default {
  name: 'App',
  components: {
    MenSection,
    WomenSection,
    UnavailableProduct
  },
  data() {
    return {
      category: 'Women' // Ganti dengan kategori aktif yang sesuai
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
