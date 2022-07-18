<template>
  <img src="@/assets/forma1.png" :class="variant" class="fixed top-0 left-0"/>
</template>

<script>
export default {
    name: 'AtomFormOne',
    props: {
        variant: {
            type: String,
            required: true,
            default: 'bg-light-gray-adopet'
        }
    }
}
</script>

<style lang="scss">

</style>