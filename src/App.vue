<template>
    <div id="app" class="d-flex flex-column min-vh-100">
      <NavBar />
      <MainHeader />
      <SectionFeatures />
      <SectionAbout />
      <SectionPricing />
      <UsersSection />
      <SectionContact />
      <ComponentFooter />

      <!-- Botón Volver Arriba -->
      <button @click="scrollToTop" class="btn-back-to-top">
        <i class="fas fa-arrow-up"></i>
      </button>
    </div>
  </template>

  <script>
  import NavBar from './components/NavBar.vue';
  import MainHeader from './components/MainHeader.vue';
  import SectionFeatures from './components/SectionFeatures.vue';
  import SectionPricing from './components/SectionPricing.vue';
  import SectionAbout from './components/SectionAbout.vue';
  import UsersSection from './components/UserSection.vue';
  import SectionContact from './components/SectionContact.vue';
  import ComponentFooter from './components/ComponentFooter.vue';

  export default {
    name: 'App',
    components: {
      NavBar,
      MainHeader,
      SectionFeatures,
      SectionPricing,
      SectionAbout,
      UsersSection,
      SectionContact,
      ComponentFooter
    },
    methods: {
      scrollToTop() {
        window.scrollTo({
          top: 0,
          behavior: 'smooth'
        });
      }
    }
  }
  </script>

  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    position: relative; /* Añadido para posicionamiento relativo */
  }

  /* Estilos para el botón Volver Arriba */
  .btn-back-to-top {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #2ECC71; /* Color verde claro */
    color: #ECF0F1; /* Texto en blanco */
    border: none;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    font-size: 1.5rem;
    cursor: pointer;
    z-index: 1000; /* Asegura que esté por encima de otros elementos */
    transition: background-color 0.3s ease;
  }

  .btn-back-to-top i {
    transition: transform 0.3s ease;
  }

  .btn-back-to-top:hover {
    background-color: #27AE60; /* Color verde claro más oscuro al pasar el mouse */
  }

  .btn-back-to-top:hover i {
    transform: scale(1.2); /* Efecto de escala al pasar el mouse */
  }

  /* Estilos generales */
  body {
    margin: 0;
    padding: 0;
  }

  </style>
