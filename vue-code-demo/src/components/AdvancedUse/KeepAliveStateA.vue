<template>
  <div>
    <h2>{{ time1 }}</h2>
    <p>{{ time }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      time: 1,
      time1: 1,
    }
  },
  props: {
    msg: String,
  },
  created() {
    console.log('A created')
    this.time1 = new Date().getMilliseconds()
  },
  mounted() {
    // eslint-disable-next-line
    console.log('A mounted')
  },
  activated() {
    this.time = new Date()
    console.log('a activated')
  },
  deactivated() {
    console.log('a deactivated')
  },
  beforeUpdate() {
    console.log('a beforeUpdate')
  },
  updated() {
    console.log('a updated')
  },
  beforeDestroy() {
    console.log('a beforedestory')
  },
  destroyed() {
    // eslint-disable-next-line
    console.log('A destroyed')
  },
}
</script>
