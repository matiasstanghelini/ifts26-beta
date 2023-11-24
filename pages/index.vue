<template>
  <div>
    <header class="navbar navbar-light navbar-expand-lg" role="banner">
      <a class="skip-to-main-content-link"> Ir al contenido principal </a>
      <div class="container header-container">
        <a href="/inicio" class="navbar-brand">
          <img
            src="~/assets/img/logo.png"
            class="img-logo"
            role="img"
            aria-label="Instituto de Formación Técnica Superior Nº26"
            jsname="SwcDWb" />
          <span>IFTS Nº2 </span>
        </a>
        <div class="navbar-login-mobile">
          <a
            class="btn btn-lg btn-icon btn-outline-link"
            href="#"
            target="_blank">
            <span class="material-icons-round">person</span>
            <span class="btn-text">Ingresar</span>
          </a>
        </div>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarContent"
          aria-controls="navbarContent"
          aria-expanded="false"
          aria-label="Menú"></button>
        <div class="collapse navbar-collapse" id="navbarContent">
          <div class="navbar-content">
            <div class="navbar-login">
              <a
                class="btn btn-lg btn-icon btn-outline-link"
                href="#"
                target="_blank">
                <span class="material-icons-round">person</span>
                <span class="btn-text">Ingresar</span>
              </a>
            </div>
          </div>
          <div class="navbar-content-extended">
            <nuxt-link to="/">
              <h3 class="navbar-sections-title">Secciones</h3>
            </nuxt-link>
            <nav>
              <ul class="nav nav-pills nav-sections">
                <li class="nav-item">
                  <nuxt-link to="/inicio">
                    <a class="nav-link nav-link-lg">
                      <span>Inicio</span>
                    </a>
                  </nuxt-link>
                </li>
                <li class="nav-item">
                  <nuxt-link to="/preinscripcion">
                    <a class="nav-link nav-link-lg" href="#">
                      <span>Preinscripcion</span>
                    </a></nuxt-link
                  >
                </li>
                <li class="dropdown">
                  <button
                    type="button"
                    class="btn btn-dropdown btn-dropdown-lg dropdown-toggle"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false">
                    <span class="btn-dropdown-text">Institucional</span>
                    <span class="material-icons-round btn-dropdown-icon">
                      expand_more
                    </span>
                  </button>
                  <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Calendario académico</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Datos Institucionales </span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Reglamento Carreras </span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Reglamento Orgánico</span>
                    </a>
                    <a class="dropdown-item item-link" href="#">
                      <span class="item-text">Otro Link</span>
                      <span class="material-icons-round">arrow_forward</span>
                    </a>
                  </div>
                </li>

                <li class="dropdown">
                  <button
                    type="button"
                    class="btn btn-dropdown btn-dropdown-lg dropdown-toggle"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false">
                    <span class="btn-dropdown-text">Carreras</span>
                    <span class="material-icons-round btn-dropdown-icon">
                      expand_more
                    </span>
                  </button>
                  <div class="dropdown-menu">
                    <a class="dropdown-item item-link" href="#">
                      <span class="item-text">Gestión Int. Riesgo</span>
                      <span class="material-icons-round">arrow_forward</span>
                    </a>
                    <a class="dropdown-item item-link" href="#">
                      <span class="item-text">HyS en el Trabajo</span>
                      <span class="material-icons-round">arrow_forward</span>
                    </a>
                  </div>
                </li>
                <li class="dropdown">
                  <button
                    type="button"
                    class="btn btn-dropdown btn-dropdown-lg dropdown-toggle"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false">
                    <span class="btn-dropdown-text">Alumnos</span>
                    <span class="material-icons-round btn-dropdown-icon">
                      expand_more
                    </span>
                  </button>
                  <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Constancias</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Becas</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Tutorías</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Equivalencias</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Títulos extranjeros</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Matrícula Profesional</span>
                    </a>
                    <a class="dropdown-item" href="#">
                      <span class="item-text">Horarios {{ currentYear }}</span>
                    </a>
                  </div>
                </li>

                <li class="nav-item">
                  <a class="nav-link nav-link-lg" href="#">
                    <span>Campus virtual</span>
                  </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link nav-link-lg" href="#">
                    <span>Novedades y Publicaciones</span>
                  </a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
      <div class="header-backdrop"></div>
    </header>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
};
</script>

<style>
.img-logo {
  display: inline-block;
  max-height: 56px;
  max-width: 225px;
}
</style>
