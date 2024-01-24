<script>
export default {
  name: 'App',
  data() {
    return {
      name: 'Todolist',
      list: [
        {
          text: 'war machine',
          done: true
        },
        {
          text: 'take the baby swimming',
          done: true
        },
        {
          text: 'go to the office',
          done: true
        },
        {
          text: 'collect the clothes',
          done: true
        },
        {
          text: 'go shopping',
          done: true
        }
      ],
    }
  },
  mounted() {
    console.log(this.slider);
  }
}
</script>

<template>
  <header>
    <h1>{{ name }}</h1>

  </header>
  <main>
    <ul>
      <li v-for="item in list">
        {{ item.text }}
      </li>
    </ul>

  </main>
</template>

<style>
ul {
  color: white;
}
</style>
