
<template>

  <section class="src-componentes-navbar">
    <nav class="navbar navbar-expand-md navbar-dark bg-dark">

      <!-- ruta root -->
      <router-link to="/">
        <a class="navbar-brand" href="#">Inicio</a>
      </router-link>

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">

          <li class="nav-item">
            <router-link to="/Formulario">
              <a class="nav-link" href="#">Formulario</a>
            </router-link>
          </li>

          <li class="nav-item">
            <router-link to="/MockApi">
              <a class="nav-link" href="#">MockApi</a>
            </router-link>
          </li>

        </ul>
      </div>
    </nav>
  </section>

</template>

<script>

  export default  {
    name: 'navbar-component',
    props: [],
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="css">
</style>
