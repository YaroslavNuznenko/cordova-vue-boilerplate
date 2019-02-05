<template>
  <div class="hello">
    <form action="" class="form">
      <div class="label">Login: </div>
      <input class='input' type="text">
      <div class="label">Password: </div>
      <input class='input' type="password">
      <input class='button' type="submit">
    </form>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
.form {
  width: 200px;
  margin: 0 auto;
  padding: 10px;
  text-align: left;
  background: #e1e8d9;
  border-radius: 5px;
}

.label {
  margin-bottom: 2px;
}

.input {
  margin-bottom: 5px;
}
</style>
