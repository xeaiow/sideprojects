<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      工作後不忘持續關注新技術，將練習的結果記錄下來，於是此網站便誕生。
    </p>
    <h3>Vue</h3>
    <ul>
      <li><a href="#" target="_blank">Dcard 圖片下載器</a></li>
    </ul>
    <h3>JWT</h3>
    <ul>
      <li>none</li>
    </ul>
    <h3 class="italic">React</h3>
    <ul>
      <li>none</li>
    </ul>
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
.italic {
  font-style: italic;
}
</style>
