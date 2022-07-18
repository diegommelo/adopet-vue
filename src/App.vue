<template>
  <div id="app" class="flex flex-col min-h-screen">
    <organism-header class="h-36"/>
    <main class="flex grow">
      <router-view/>
    </main>
    <organism-footer class="flex items-center justify-center h-24"/>
  </div>
</template>


<script>
import OrganismFooter from './components/organisms/footer/OrganismFooter.vue';
import OrganismHeader from './components/organisms/header/OrganismHeader.vue';

export default {
  name: 'App',
  components: {
    OrganismHeader,
    OrganismFooter,
  }
}
</script>

<style lang="scss">

  
</style>
