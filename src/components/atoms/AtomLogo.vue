<template>
    <div class="w-full">
        <img :src="require(`@/assets/logo-${variant}.png`)" :class="size" class="m-auto"/>
    </div>
</template>

<script>
export default {
    name: 'AtomLogo',
    props: {
        variant: {
            type: String,
            required: true
        },
        size: {
            type: String,
            default: "w-48"
        }
    },
}
</script>