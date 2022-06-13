<template>
  <div id = "app">
    <!-- {{message}}
    <h2>뒤집힌 message</h2>
    {{reverseMessage}} -->
    <input v-model = "firstname"/>
    <input v-model = "secondname"/>

    <h2>full name</h2>
    <span>{{fullname}}</span>
  </div>
</template>
<script>
export default {
  name: 'app',
  data() {
    return {
      // message: 'Hello Vue !!'
      firstname: '',
      secondname: ''
    }
  },
  // computed: {
  //   reverseMessage () {
  //     return this.message.split("").reverse().join("");
  //   }
  // }


  // watch: {
  //   firstname (val) {
  //     this.fullname = `${val} ${this.secondname}`
  //   },
  //   secondname (val) {
  //     this.fullname = `${this.firstname} ${val}`
  //   }
  // }


  computed: {
    fullname() {
      return `${this.firstname} ${this.secondname}`
    }
  }
}
</script>
<style lang="">
  
</style>