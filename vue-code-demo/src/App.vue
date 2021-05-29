<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <!-- <TplDemo /> -->
    <!-- <ConditionDemo/> -->
    <!-- <EventDemo /> -->

    <!-- <ComponentDemo /> -->

    <AdvancedUse />
    <!-- <test>ttt</test> -->

    <!-- <CartDemo/> -->
    <!-- <computedDemo /> -->
    <!-- <WatchDemo></WatchDemo> -->
    <!-- <ListDemo></ListDemo> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// import TplDemo from './components/BaseUse/TplDemo'
// import ConditionDemo from './components/BaseUse/ConditionDemo'
// import EventDemo from './components/BaseUse/EventDemo'

// import ComponentDemo from './components/ComponentsDemo/index'

import AdvancedUse from './components/AdvancedUse/index'
// import test from './components/AdvancedUse/test'

// import CartDemo from './components/Cart/index'
// import computedDemo from './components/BaseUse/ComputedDemo'
// import WatchDemo from './components/BaseUse/WatchDemo'
// import ListDemo from './components/BaseUse/ListDemo'
export default {
  name: 'app',
  components: {
    // HelloWorld
    // EventDemo,
    // ComponentDemo,
    AdvancedUse,
    // test,
    // CartDemo
    // TplDemo,
    // computedDemo,
    // WatchDemo,
    // ListDemo,
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
