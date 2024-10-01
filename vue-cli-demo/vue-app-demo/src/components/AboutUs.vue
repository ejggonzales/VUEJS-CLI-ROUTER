<template>
    <div id="about-us">
      <div id="todo-card">
          <div class="container">
              <div class="alert alert-primary" role="alert">
                  <h1>{{ msg6 }}</h1>
              </div>
          </div>
      </div>
      
    </div>
  </template>
  
  <script>
  export default {
    name: 'about-us',
    data () {
      return {
        msg6: 'This is the About component'
      }
    }
  }
  </script>
  
  <style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  
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
  