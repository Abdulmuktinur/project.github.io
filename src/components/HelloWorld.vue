<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Vin's Care, Kami bergerak pada bidang pelayanan jasa <br>
    perawatan sepatu yang berlokasi di Sidoarjo Jawa Timur Sob.</p>
    <p class="title">Pelayanan</p>
    <ul>
      <li><a href="#" target="_blank" rel="noopener">Fast Clean</a></li>
      <li><a href="#" target="_blank" rel="noopener">Deep Clean</a></li>
      <li><a href="#" target="_blank" rel="noopener">Unyellowing</a></li>
      <li><a href="#" target="_blank" rel="noopener">Recoloring</a></li>
    </ul>
    <button type="button" class="btn btn-warning text-black">Follow Us</button>
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
p.title{
  margin: auto;
  font-size : 20px;
  font-weight : bold;
}
strong{
  font-size: 20px;
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
  color: #000000;
}
</style>
