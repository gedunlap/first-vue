<template>

<div>
  <Navbar />
  <BigImage />
  <TrialComp />
  <h1>Hello Garrett</h1>
  <h2>Dog Name: {{dog}}</h2>
  <button v-on:click="handleClick">Click Me</button>
  <HelloWorld v-bind:otherDog="otherDog" />
</div>

</template>

<script>
import HelloWorld from "./components/HelloWorld.vue"
import Navbar from "./components/Navbar.vue"
import BigImage from "./components/BigImage.vue"
import TrialComp from "./components/TrialComp.vue"

export default {
  name: 'App',
  data: function(){
    return {
      dog: "Weeman",
      otherDog: "Lincoln"
    }
  },
  components: {
    HelloWorld,
    Navbar,
    BigImage,
    TrialComp
  },
  methods: {
    handleClick: function(){
      this.dog = "Delilah"
      this.otherDog = "Mandy"
    }
  }
}

</script>

<style>

* {
  padding: 0px;
  margin: 0px;
}

h1 {
  color: blue;
}

h3 {
  color: teal;
}

</style>