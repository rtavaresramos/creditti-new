<template>
  <div>
    <div class="container">
    <navbar />
      <nuxt />
    </div>
  </div>
</template>

<script>
export default {
  head:{
    title: 'Creditti',
    link: [
      {
        rel: 'stylesheet',
        href: 'https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,300;0,600;0,700;0,800;0,900;1,400&display=swap'
      }
    ]
  }
}
</script>

<style>
/* @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,300;0,600;0,700;0,800;0,900;1,400&display=swap'); */
body,html,* {
  font-family: 'Raleway', sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  outline: none;
  overflow-x: hidden!important;
}

body{
  display: flex;
  justify-content: center;
  width: 100%;
  font-size: 14px;
  background: #E8EAEB;
}
a{
  text-decoration: none;
}
.container{
  max-width: 1368px!important;
}
</style>