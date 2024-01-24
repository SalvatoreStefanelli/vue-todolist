<script>
export default {
  name: 'App',
  data() {
    return {
      slider: {
        name: 'Todolist',
        text: ['war machine', 'take the baby swimming', 'go to the office', 'collect the clothes', 'go shopping'],
        done: true
      }
    }
  },
  mounted() {
    console.log(this.todo);
  }
}
</script>

<template>
  <header>
    <h1>{{ slider.name }}</h1>
    <p></p>
  </header>
</template>

<style></style>
