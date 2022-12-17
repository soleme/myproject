<template>
  <div>
    안녕하세요
    <vue-person
        ref="VuePerson"
        name="dorosy"
    />
  </div>
</template>

<script>
import VuePerson from './components/VuePerson.vue'

export default {
  name: 'App',
  components: {
    VuePerson,
  },
  mounted() {
    const name = this.$refs.VuePerson.name
    console.log('name', name) // name dorosy
  }
}
</script>