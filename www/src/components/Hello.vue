<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad autem beatae blanditiis, enim eveniet id magnam quae quod recusandae sint totam, vel, vitae voluptatem? Corporis cupiditate doloribus nisi veniam vitae.
  </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello World!'
    }
  }
}
</script>

<style>
  .hello {
    background-color: #00b9d8;
    border: 1px;
  }
</style>
