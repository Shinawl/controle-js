<template>
  <div class="hello">
    <button class="button">Save and continue</button>
  </div>
</template>

<script>
export default {
  name: 'Button',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .button {
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    background-color: #f44336;
    border: 2px solid #f44336;
    border-radius: 20px;
    transition-duration: 0.4s;
  }

  .button:hover {
    background-color: white;
    color: black;
  }
</style>
