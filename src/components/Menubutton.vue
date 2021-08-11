<template>
  <b-container class="bv-example-row">
    <b-row>
      <b-col>1 of 3</b-col>
      <b-col>2 of 3</b-col>
      <b-col>3 of 3</b-col>
    </b-row>
  </b-container>
</template>



<script>
export default {
  name: 'Home',
  data () {
    return {
    }
  },
  methods: {
    hello_world() {
      console.log('Hello world - button trigger event working!')
    }
  }
}
</script>