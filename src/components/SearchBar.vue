<template>
  <div>
    <input @input="onInput" />
  </div>
</template>

<script>
export default {
  name: 'SearchBar',
  methods: {
    onInput: function() {
      // console.log(event.target.value)
    }
  }
}
</script>

<style >

</style>