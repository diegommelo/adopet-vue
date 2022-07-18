<template>
  <div class="bg-blue-adopet flex justify-center align-center text-center">
    <atom-form-one variant="bg-blue-adopet" />
    <div class="z-10 w-9/12 mt-2">
      <atom-logo variant="white" />
      <h2>Boas-vindas!</h2>
      <p>Que tal mudar sua vida adotando seu novo melhor amigo? Vem com a gente!</p>
    </div>
  </div>
</template>

<script>
import AtomLogo from '@/components/atoms/AtomLogo.vue'
import AtomFormOne from '@/components/atoms/AtomFormOne.vue'

export default {
  name: 'HomeView',
  components: {
    AtomLogo,
    AtomFormOne
  }
}
</script>

<style lang="scss">
</style>
