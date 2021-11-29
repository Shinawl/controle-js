<template>
  <div class="hello">
    <p>Choose one of the available timeslots</p>

    <div>
      <input type="radio" id="huey" name="drone" value="huey">
      <label for="huey">Huey</label>
    </div>

    <div>
      <input type="radio" id="dewey" name="drone" value="dewey">
      <label for="dewey">Dewey</label>
    </div>

      <div>
      <input type="radio" id="louie" name="drone" value="louie">
      <label for="louie">Louie</label>
    </div>

  </div>
</template>

<script>
export default {
  name: 'TimeInput',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
