<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle titleText="My Random Musings" subTitle="So Very Very Random"></MyTitle>
    <DescriptorSection imageId=100 sectionTitle="A Thing I Saw" sectionText="It was just so thingy"></DescriptorSection>
    <DescriptorSection imageId=101 sectionTitle="What is this?" sectionText="I just don't know!"></DescriptorSection>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import DescriptorSection from './components/DescriptorSection.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    DescriptorSection
  }
}
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
