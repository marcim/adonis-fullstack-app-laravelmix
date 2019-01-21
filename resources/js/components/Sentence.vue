<template>
  <div class="subtitle">
    <p>{{text}}</p>
    <p>
      Don't know where to start? Read the <a href="https://adonisjs.com/docs">documentation</a>.
    </p>
  </div>
</template>

<script>
  export default {
    name: 'sentence-component',

    data() {
      return {
        text: 'AdonisJs simplicity will make you feel confident about your code'
      }
    }
  }
</script>
