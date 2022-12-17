<template>
  <div>
    Hi
  </div>
</template>

<script>
export default {
  name: "VuePerson",
  props: {
    name : {
      type: String,
      default: ''
    }
  },
  methods: {
    sayHi(){
      console.log(`Hi My name is ${this.name}`);
    }
  }
}
</script>

<style scoped>

</style>