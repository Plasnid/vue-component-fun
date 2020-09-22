<template>
    <section>
        <img v-bind:src="imageGrabber()" alt="">
        <h2>{{ sectionTitle }}</h2>
        <p>{{ sectionText }}</p>
    </section>
</template>

<script>
export default {
    name: "DescriptorSection",
    props: {
        sectionTitle: {
            type: String,
            default: ""
        },
        sectionText:{
            type: String,
            default:""
        },
        imageId:{
            type: Number,
            default:1
        }
    },
    methods: {
        imageGrabber() {
            return `https://picsum.photos/id/${this.imageId}/200/`
        }
    },
    
}
</script>

<style>

</style>