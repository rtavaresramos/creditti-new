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
        href: 'https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,400&display=swap'
      },
      {
        rel: 'stylesheet',
        href: 'https://pro.fontawesome.com/releases/v5.10.0/css/all.css',
        integrity:"sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p",
        crossorigin:"anonymous"
      },
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
  scroll-behavior: smooth;
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
.text-start{
  text-align: left;
}
.text-center{
  text-align: center;
}
.text-end{
  text-align: right;
}
.d-flex{
  display: flex;
}
.flex-col{
  flex-direction: column;
}
.flex-wrap{
  flex-wrap: wrap;
}
.align-center{
  align-items: center;
}
.align-start{
  align-items: flex-start;
}
.align-end{
  align-items: flex-end;
}
.justify-end{
  justify-content: flex-end;
}
.justify-center{
  justify-content: center;
}
.justify-between{
  justify-content: space-between;
}
.justify-around{
  justify-content: space-around;
}
.mt-5{
margin-top: 50px;
}
.mt-3{
margin: 12px 0 0;
}
.my-2{
margin: 8px 0;
}
.my-3{
margin: 12px 0;
}
.mx-2{
margin:0 8px;
}
.mx-5{
margin:0 40px;
}
</style>