<template>
  <div class="hello">
    <h3>CInfo about available timslots</h3> <br>
    <p>Regular slots          <span id="vert">Premium slots</span>          <span id="violet">Prime slots</span></p>
  </div>
</template>

<script>
export default {
  name: 'InfoTime',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#vert {
  color: green;
}
#violet {
  color: violet;
}
</style>
