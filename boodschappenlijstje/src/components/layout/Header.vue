<template>
  <header class="header">
    <div class="Ikea">
    <h1>IKEA<span style="font-size: 13px; vertical-align: text-top;">®</span> Boorschappen Lijstje</h1>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">Over ons</router-link>
    </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
  .header {
    background: #004FB5;
    color: #F8D500;
    text-align: center;
    padding: 30px;
  }

  .header a {
    color: #004FB5;
    background: #F8D500;
    border-radius: 30px;
    padding: 10px;
    text-decoration: none;
  }
  .Ikea
  {
    color: #004FB5;
    background: #F8D500;
    width: 100%;
    height: 100px;
    border-radius: 60%;
  }
  

</style>


