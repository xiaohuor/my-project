<template>
  <div>
    <h1>I'm Kitty</h1>
    <p>who are you?</p>
    <p>{{message}}</p>
  </div>
</template>

<script>
export default {
  name: "Kitty",
  data () {
    return {
      message: "I'm hungry. About you?"
    }
  }
}
</script>
<style>
.message{
  text-decoration: underline;
}
</style>

