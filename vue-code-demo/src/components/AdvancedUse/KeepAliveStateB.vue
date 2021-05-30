<template>
  <p>state B</p>
</template>

<script>
export default {
  mounted() {
    // eslint-disable-next-line
    console.log('B mounted')
  },
  activated() {
    console.log('b activated')
  },
  deactivated() {
    console.log('b deactivated')
  },
  beforeUpdate() {
    console.log('b beforeUpdate')
  },
  updated() {
    console.log('b updated')
  },
  beforeDestroy() {
    console.log('b beforedestory')
  },
  destroyed() {
    // eslint-disable-next-line
    console.log('B destroyed')
  },
}
</script>
