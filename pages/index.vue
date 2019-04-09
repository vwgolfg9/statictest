<template>
  <div>
    <app-header></app-header>
    <app-main></app-main>
    <h1 style="margin-top:20px; font-size: 30px;">This is index</h1>
  </div>
</template>

<script>
import Header from "@/components/Header.vue"
import main from "@/components/main.vue"

export default {
  
  components: {
    appHeader : Header,
    appMain : main,
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
.header{
  background-color: rgb(164, 164, 240);
}
.welcome {
  color: white;
}
</style>
