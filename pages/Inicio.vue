<template>
  <div>
    <index></index>
    <div>
      <h1 class="text-center mt-5">
        Instituto de Formación Técnica Superior Nº 26
      </h1>
    </div>
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-6 mb-3">
          <nuxt-link to="/preinscripcion">
            <a class="card" href="#">
              <div class="card-body">
                <i class="bx bx-news card-icon"></i>
                <h4 class="card-title">Preinscripción</h4>
                <p class="card-text">
                  Recomendamos en este espacio no utilizar más de 3 líneas, para
                  generar una lectura óptima.
                </p>
              </div>
            </a>
          </nuxt-link>
        </div>
        <div class="col-md-6 mb-3">
          <a class="card" href="">
            <div class="card-body">
              <i class="bx bx-news card-icon"></i>
              <h4 class="card-title">Calendario académico</h4>
              <p class="card-text">
                Recomendamos en este espacio no utilizar más de 3 líneas, para
                generar una lectura óptima.
              </p>
            </div>
          </a>
        </div>
        <div class="col-md-6 mb-3">
          <a class="card" href="">
            <div class="card-body">
              <i class="bx bx-news card-icon"></i>
              <h4 class="card-title">Calendario académico</h4>
              <p class="card-text">
                Recomendamos en este espacio no utilizar más de 3 líneas, para
                generar una lectura óptima.
              </p>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import index from "~/pages/index.vue";
export default {
  name: "inicio",
  components: {
    index,
  },
};
</script>
