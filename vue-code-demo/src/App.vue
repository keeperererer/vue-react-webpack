<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <!-- <TplDemo /> -->
    <!-- <ConditionDemo/> -->
    <!-- <EventDemo/> -->

    <!-- <ComponentDemo/> -->

    <!-- <AdvancedUse/> -->

    <!-- <CartDemo/> -->
    <!-- <computedDemo /> -->
    <WatchDemo></WatchDemo>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// import TplDemo from './components/BaseUse/TplDemo'
// import ConditionDemo from './components/BaseUse/ConditionDemo'
// import EventDemo from './components/BaseUse/EventDemo'

// import ComponentDemo from './components/ComponentsDemo/index'

// import AdvancedUse from './components/AdvancedUse/index'

// import CartDemo from './components/Cart/index'
// import computedDemo from './components/BaseUse/ComputedDemo'
import WatchDemo from './components/BaseUse/WatchDemo'

export default {
  name: 'app',
  components: {
    // HelloWorld
    // EventDemo
    // ComponentDemo
    // AdvancedUse
    // CartDemo
    // TplDemo,
    // computedDemo,
    WatchDemo
  },
}
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
