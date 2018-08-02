<template>
  <div id="app">
    <div id="cover"></div>
    <Header></Header>
    <Todo></Todo>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/header.vue'
import Footer from './components/footer.vue'
import Todo from './components/todo.vue'
export default {
  components: {
    Header,
    Footer,
    Todo
  }
}
</script>
<style scoped>
#app{
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
}
#cover{
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background-color:#999;
  opacity: .8;
  z-index: -1;
}
</style>
