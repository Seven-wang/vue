<template>
  <div class="hello">
    <p>{{ msga }}</p>
    <input v-model="msga">
  </div>
</template>

<script>
export default {
  data () {
    return {
      msga: 'Hello World!'
    }
  }
}
</script>
