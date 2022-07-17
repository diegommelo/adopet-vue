<template>
  <div id="app" class="h-screen">
    <organism-header />
    <main class="grid sm:grid-cols-4 sm:gap-4">
      <router-view/>
    </main>
    <organism-footer />
  </div>
</template>


<script>
import OrganismFooter from './components/organisms/footer/OrganismFooter.vue';
import OrganismHeader from './components/organisms/header/OrganismHeader.vue';

export default {
  name: 'App',
  components: {
    OrganismHeader,
    OrganismFooter
  }
}
</script>

<style lang="scss">
  #app {
    background: url('@/assets/forma1.png') no-repeat left top;
    background-size: contain;
  }

</style>
