<template>
  <div class="Infos">
    <h3>Can't find the time you are looking for ?</h3> <br>
    <p>You have been added to the waiting list <span>Remove</span> </p>
  </div>
</template>

<script>
export default {
  name: 'OtherAction',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
span {
  color: Red;
}
</style>
