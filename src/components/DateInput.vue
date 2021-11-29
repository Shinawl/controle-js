<template>
  <div class="Date">
    <label for="start">Select a day</label>

<input type="date" id="start" name="trip-start"
       value=""
       min="" max="">
  </div>
</template>

<script>
export default {
  name: 'DateInput',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
