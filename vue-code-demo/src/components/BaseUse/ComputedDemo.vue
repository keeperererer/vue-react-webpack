<template>
  <div>
    <!--1.直接拼接:语法过于繁琐-->
    <h2>{{ firstName }} {{ lastName }}</h2>

    <!--2.通过定义methods-->
    <h2>{{ getFullName() }}</h2>
    <h2>{{ getFullName() }}</h2>
    <h2>{{ getFullName() }}</h2>
    <h2>{{ getFullName() }}</h2>

    <!--3.通过computed-->
    <h2>{{ fullName }}</h2>
    <h2>{{ fullName }}</h2>
    <h2>{{ fullName }}</h2>
    <h2>{{ fullName }}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      firstName: 'Kobe',
      lastName: 'Bryant',
    }
  },
  computed: {
    fullName: function() {
      console.log('1')
      return this.firstName + ' ' + this.lastName
    },
  },
  methods: {
    getFullName: function() {
      console.log('2')
      return this.firstName + ' ' + this.lastName
    },
  },
}
</script>
