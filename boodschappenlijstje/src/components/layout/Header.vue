<template>
<div id="app">
   <Push>
      <a id="home" href="#">
        <span>Home</span>
      </a>
    </Push>
<main id="page-wrap">
  <header class="header">
    <img src="../../../images/ikeagif.gif" id="logo">
  </header>
   </main>
</div>
</template>

<script>

import { Push } from 'vue-burger-menu'  // import the CSS transitions you wish to use, in this case we are using `Slide`
 
export default {
  name: "Header",
    components: {
        Push // Register your component
    }
}

</script>

<style >
  .header {
    background: white;
    text-align: center;
    padding: 30px;
    height: 100px;
  }
  #logo
  {
    height: 500%;
    margin-top: -5.5%;
    margin-left: -90%;
  }
  img{
    padding-left: 10%;
  }

/*BURGER */
   .bm-burger-button {
      position: fixed;
      width: 36px;
      height: 30px;
      left: 36px;
      top: 36px;
      cursor: pointer;
    }
    .bm-burger-bars {
      background-color: pink;
    }
    .line-style {
      position: absolute;
      height: 20%;
      left: 0;
      right: 0;
    }
    .cross-style {
      position: absolute;
      top: 12px;
      right: 2px;
      cursor: pointer;
    }
    .bm-cross {
      background: blue;
    }
    .bm-cross-button {
      height: 24px;
      width: 24px;
    }
    .bm-menu {
      height: 100%; /* 100% Full-height */
      width: 0; /* 0 width - change this with JavaScript */
      position: fixed; /* Stay in place */
      z-index: 1000; /* Stay on top */
      top: 0;
      left: 0;
      background-color: orange; /* Black*/
      overflow-x: hidden; /* Disable horizontal scroll */
      padding-top: 60px; /* Place content 60px from the top */
      transition: 0.5s; /*0.5 second transition effect to slide in the sidenav*/
    }
 
    .bm-overlay {
      background: white;
    }
    .bm-item-list {
      color: #b8b7ad;
      margin-left: 10%;
      font-size: 20px;
    }
    .bm-item-list > * {
      display: flex;
      text-decoration: none;
      padding: 0.7em;
    }
    .bm-item-list > * > span {
      margin-left: 10px;
      font-weight: 700;
      color: white;
    }
  

</style>


