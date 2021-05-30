<template>
  <p>state C</p>
</template>

<script>
export default {
  mounted() {
    // eslint-disable-next-line
    console.log('C mounted')
  },
  activated() {
    console.log('c activated')
  },
  deactivated() {
    console.log('c deactivated')
  },
  beforeUpdate() {
    console.log('c beforeUpdate')
  },
  updated() {
    console.log('c updated')
  },
  beforeDestroy() {
    console.log('c beforedestory')
  },
  destroyed() {
    // eslint-disable-next-line
    console.log('C destroyed')
  },
}
</script>
