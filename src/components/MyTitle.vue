<template>
    <header>
        <h1>{{ titleText }}</h1>
        <h2>{{ subTitle }}</h2>
    </header>
</template>

<script>
export default {
    name: 'MyTitle',
    props: {
        titleText: {
            type: String,
            default: "I'm so sad I don't have a title yet!"
        },
        subTitle:{
            type: String,
            default:"I am not the most important Title"
        }
    },
}
</script>

<style>

</style>