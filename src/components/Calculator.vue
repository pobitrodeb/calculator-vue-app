<template>
  <div class="hello">
  {{ msg }}
  </div>
  <div class="col-md-6">
    <table class="table table-bordered">
  <thead>
    <tr>
      <th scope="col">C</th>
      <th scope="col"><i class="fa-solid fa-plus"></i>/-</th>
      <th scope="col"><i class="fa-solid fa-percent"></i></th>
      <th scope="col"><i class="fa-solid fa-divide"></i></th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <td>7</td>
      <td>8</td>
      <td>9</td>
      <td><i class="fa-solid fa-x"></i></td>
    </tr>

    <tr>
      <td>4</td>
      <td>5</td>
      <td>6</td>
      <td><i class="fa-solid fa-minus"></i></td>
    </tr>

    <tr>
      <td>1</td>
      <td>2</td>
      <td>3</td>
      <td><i class="fa-solid fa-plus"></i></td>
    </tr>

    <tr>
      <td colspan="2">0</td>
      <td><i class="fa-solid fa-circle-dot"></i></td>
      <td><i class="fa-solid fa-equals"></i></td>
    </tr>

  </tbody>
</table>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
