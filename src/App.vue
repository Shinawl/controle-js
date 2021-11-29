<template>
  <DateInput />
  <TimeInput />
  <InfoTime />
  <OtherAction />
  <Button />
</template>

<script>
import DateInput from './components/DateInput.vue'
import TimeInput from './components/TimeInput.vue'
import InfoTime from './components/InfoTime.vue'
import OtherAction from './components/OtherAction.vue'
import Button from './components/Button.vue'

export default {
  name: 'App',
  components: {
    DateInput,
    TimeInput,
    InfoTime,
    OtherAction,
    Button
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
