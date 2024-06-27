<template>
    <section class="features py-5">
      <div class="container">
        <h2 class="section-title text-center mb-5">Características Principales</h2>
        <div class="row">
          <div class="col-md-4 text-center mb-5">
            <div class="feature-icon mb-4">
              <i class="fas fa-map-marked-alt fa-4x animated-icon"></i>
            </div>
            <h4 class="feature-title mb-3">Exploración de Leyendas</h4>
            <p class="feature-description">Descubre y explora las leyendas más fascinantes de cada estado de México.</p>
          </div>
          <div class="col-md-4 text-center mb-5">
            <div class="feature-icon mb-4">
              <i class="fas fa-users fa-4x animated-icon"></i>
            </div>
            <h4 class="feature-title mb-3">Personajes Auténticos</h4>
            <p class="feature-description">Interactúa con personajes inspirados en figuras históricas y mitológicas mexicanas.</p>
          </div>
          <div class="col-md-4 text-center mb-5">
            <div class="feature-icon mb-4">
              <i class="fas fa-puzzle-piece fa-4x animated-icon"></i>
            </div>
            <h4 class="feature-title mb-3">Desafíos</h4>
            <p class="feature-description">Resuelve desafíos únicos para avanzar en tu aventura y descubrir secretos ocultos.</p>
          </div>
        </div>
      </div>
    </section>
  </template>

  <script>
  export default {
    name: 'SectionFeatures',
    mounted() {
      this.animateIcons();
    },
    methods: {
      animateIcons() {
        // Simular animación de iconos flotantes usando CSS
        const icons = document.querySelectorAll('.animated-icon');
        icons.forEach(icon => {
          icon.classList.add('float-icon');
        });
      }
    }
  }
  </script>

  <style scoped>
  .features {
    background-color: #000000; /* Color de fondo oscuro */
    color: #ffffff; /* Texto en color blanco */
    padding: 60px 0;
  }

  .section-title {
    font-size: 2.8rem;
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #DAA520; /* Color dorado */
  }

  .feature-icon {
    color: #2ECC71; /* Color verde */
  }

  .feature-title {
    font-size: 1.8rem;
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #ffffff; /* Texto en color blanco */
  }

  .feature-description {
    font-size: 1.125rem;
    line-height: 1.8;
  }

  .animated-icon {
    transition: transform 0.5s ease-in-out;
  }

  .float-icon {
    animation: floatAnimation 3s ease-in-out infinite alternate;
  }

  @keyframes floatAnimation {
    0% {
      transform: translateY(0);
    }
    100% {
      transform: translateY(-10px);
    }
  }

  @media (max-width: 768px) {
    .feature-title {
      font-size: 1.5rem;
    }
  }
  </style>
