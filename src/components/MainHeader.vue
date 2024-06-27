<template>
    <header class="header">
      <video autoplay muted loop class="background-video">
        <source src="@/assets/Header.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="overlay"></div>
      <div class="container h-100 d-flex flex-column justify-content-center align-items-center text-center">
        <h1 class="text-gold mb-3">Bienvenido a Tesoro Azteca</h1>
        <p class="description mb-4">Embárcate en una aventura épica, conoce las leyendas y culturas de México.</p>

      </div>
    </header>
  </template>

  <script>
  export default {
    methods: {
      login() {
        alert('Redirigir a la página de inicio de sesión');
      },
      register() {
        alert('Redirigir a la página de registro');
      }
    }
  }
  </script>

  <style scoped>
  .header {
    position: relative;
    width: 100%;
    height: 50vh;
    overflow: hidden;
  }

  .background-video {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transform: translate(-50%, -50%);
    z-index: -1;
  }

  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    z-index: 0;
  }

  h1 {
    z-index: 1;
    position: relative;
    font-size: 3.5rem; /* Tamaño grande para impacto visual */
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #DAA520; /* Color dorado */
  }

  .description {
    z-index: 1;
    position: relative;
    font-size: 1.5rem; /* Tamaño del texto */
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #fff; /* Color blanco */
  }

  .buttons {
    z-index: 1;
    position: relative;
  }

  .btn {
    font-family: 'Cinzel', serif; /* Fuente elegante */
    font-size: 1rem; /* Tamaño de los botones */
    transition: transform 0.3s ease-in-out;
  }

  .btn-primary {
    background-color: #2ECC71; /* Verde */
    border-color: #2ECC71;
    color: #fff; /* Color blanco */
  }

  .btn-primary:hover {
    background-color: #27AE60; /* Verde más oscuro al pasar el mouse */
    border-color: #27AE60;
    transform: translateY(-5px); /* Animación de flotar */
  }

  .btn-secondary {
    background-color: #E67E22; /* Naranja */
    border-color: #E67E22;
    color: #fff; /* Color blanco */
  }

  .btn-secondary:hover {
    background-color: #D35400; /* Naranja más oscuro al pasar el mouse */
    border-color: #D35400;
    transform: translateY(-5px); /* Animación de flotar */
  }

  .float-btn {
    margin-bottom: 20px; /* Separación adicional entre botones */
  }
  </style>
