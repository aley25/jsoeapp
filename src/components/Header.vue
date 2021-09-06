<template>
  <nav id="header" class="navbar bg-dark navbar-dark fixed-top px-5">
    <a id="brand" class="navbar-brand pr-3" href="#">Jose Daniel</a>
    
    <div id="options" class="px-3">
      <a class="px-3"><router-link to="/">Inicio</router-link></a>
      <a class="px-3"><router-link to="/about">Sobre mi</router-link></a>
      <a class="px-3"><router-link to="/about">Hobbies</router-link></a>
      <a class="px-3"><router-link to="/about">Estudios</router-link></a>
      <a class="px-3"><router-link to="/about">Animes</router-link></a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
  props: {},
};
</script>
<style scoped>
#header {
  height: 5em;
}
#brand{
  text-align: left;
  justify-content: left;
}

#options{
  text-align: right;
  justify-content: right;
}


nav div li.router-link{
  padding-top: 2em;
  padding-left: 2em;
}
</style>