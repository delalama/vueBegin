<template>
  <div id="app" class="letrero">
    <bottomTitle></bottomTitle>

    <div id="texto">
      <b-card class="text-center">
        I've began to study VUE and this is a simple web to put in practice
        a bit of basic developer knowledge to delve into the subject.
        <br>
        <br>
        In a pair of days i'll try to add a basic form request.
      </b-card>
    </div>


    <b-container id="contenido " class="letrero">

      <b-btn v-b-toggle.collapse1 variant="primary">INSTALL VUE WITH BOOTSTRAP</b-btn>
      <b-collapse id="collapse1" class="mt-2">
        <b-card>
          <install_vue></install_vue>
        </b-card>
      </b-collapse>

      <b-btn v-b-toggle.collapse2 variant="primary">WHY WE LIKE VUE?</b-btn>
      <b-collapse id="collapse2" class="mt-2">
        <b-card>
          <whyVue></whyVue>
        </b-card>
      </b-collapse>

    </b-container>
    <ul>
      <li><a href="https://github.com/delalama/" target="_blank">MY GITHUB</a></li>
      <li><a href="http://178.62.92.173/EXTRA_CONTENT/FPDardos_Project/"
             target="_blank">MY SPRING + ANGULAR2 DARTS APP</a></li>
      <li><a href="http://178.62.92.173/EXTRA_CONTENT/aprendiendo/ignatius/ignatius.html"
             target="_blank">COMEDIAN WEB</a></li>
    </ul>
  </div>
</template>

<script>
    import install_vue from './components/InstallVue.vue'
    import bottomTitle from './components/BottomTitle.vue'
    import whyVue from './components/WhyVue.vue'
    export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcomeds to Your Vue.js App'
    }
  },
    components: {
        install_vue,
        bottomTitle,
        whyVue,
    }
}
</script>

<style lang="scss">

  #contenido {
    max-width: 1140px;
    border: double;
    border-color: aqua;
  }

  .smallTxt {
    margin-top: 33px;
  }
  .inl {
    display: inline;
  }
  .explain {
    font-family: "Special Elite";
    text-align: center;
  }

  .letrero {
    background-color: #343a40;
  }

  .alert {
    margin: 0 !important;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

h1, h2 {
  font-weight: bold;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

#texto {
  width: 500px;
  margin: auto;
  width: 50%;
  padding: 10px;
  font-size: 2em;
  font-family: 'Special Elite';
}
a {
  color: #42b983;
}
  #collapse2 {
    margin: auto;
    margin-top: auto;
    width: 50%;
    padding: 10px;
    width: 464px;
  }
</style>
