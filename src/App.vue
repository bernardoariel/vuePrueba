<template>
  <div class="p-field">
    <label for="fieldId">Label</label>
    <InputText id="fieldId" type="text" />
</div>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import InputText from 'primevue/inputtext';

export default {
  name: 'App',
  components: {
    InputText
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
