<template>
  <div class="hello">
    <p>Choose one of the available timeslots</p>

    <div class="choix">
        <div >
      <input type="radio" name="hour" value="hour">
      <label for="hour">12:00</label>
    </div>
    <div>
      <input type="radio" id="hour" name="hour" value="hour">
      <label for="hour">12:30</label>
    </div>
    <div>
      <input type="radio" id="hour" name="hour" value="hour">
      <label for="hour">13:00</label>
    </div>
    <div>
      <input type="radio" id="hour" name="hour" value="hour">
      <label for="hour">13:30</label>
    </div>
    

    <div class="radio-toolbar prime">
      <input type="radio" id="prime" name="hour" value="prime">
      <label for="prime">14:00</label>
    </div>
    <div class="radio-toolbar prime">
      <input type="radio" id="prime" name="hour" value="prime">
      <label for="prime">14:30</label>
    </div>
    <div class="radio-toolbar prime">
      <input type="radio" id="prime" name="hour" value="prime">
      <label for="prime">15:00</label>
    </div>

    <div class="radio-toolbar regular">
      <input type="radio" id="regular" name="hour" value="regular">
      <label for="regular">15:30</label>
    </div>
    <div class="radio-toolbar regular">
      <input type="radio" id="regular" name="hour" value="regular">
      <label for="regular">16:00</label>
    </div>

    <div class="radio-toolbar premium">
      <input type="radio" id="premium" name="hour" value="premium">
      <label for="premium">18:00</label>
    </div>
    <div class="radio-toolbar premium">
      <input type="radio" id="premium" name="hour" value="premium">
      <label for="premium">18:30</label>
    </div>
    <div class="radio-toolbar premium">
      <input type="radio" id="premium" name="hour" value="premium">
      <label for="premium">19:00</label>
    </div>
    <div class="radio-toolbar premium">
      <input type="radio" id="premium" name="hour" value="premium">
      <label for="premium">19:30</label>
    </div>
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
  /* Avec le css je test un style plutôt sympa malheureusement cela fait bugger les boutons */
  .radio-toolbar input[type="radio"] {
  opacity: 0;
  position: fixed;
  width: 0;
  }

  .radio-toolbar label {
    display: inline-block;
    background-color: #ddd;
    padding: 10px 20px;
    font-family: sans-serif, Arial;
    font-size: 16px;
    border: 2px solid #444;
    border-radius: 4px;
  }

  .radio-toolbar input[type="radio"]:checked + label {
    background-color:#bfb;
    border-color: #4c4;
  }

  .choix {
    display: flex;
  }
</style>
