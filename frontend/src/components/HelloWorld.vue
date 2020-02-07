<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>로그인화면</h2>
    <div style="display:inline-block;text-align:center;">
      <form method="post" action="/process/Login">
        <table>
            <tr>
                <td><label>ID : </label></td>
                <td><input type="text" name="id"></td>
            </tr>
            <tr>
                <td><label>PW : </label></td>
                <td><input type="text" name="passwords"></td>
            </tr>
            <tr>
                <td><input type="submit" value="Sumit" name=""></td>
            </tr>
        </table>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
