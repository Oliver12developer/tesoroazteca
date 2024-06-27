<template>
    <footer class="footer py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-4 mb-4">
            <h5 class="text-uppercase">Tesoro Azteca</h5>
            <p>Embárcate en una aventura épica, conoce las leyendas y culturas de México.</p>
            <div class="social-icons mt-4">
              <a href="https://facebook.com" target="_blank" class="me-3">
                <i class="fab fa-facebook-f fa-2x"></i>
              </a>
              <a href="https://twitter.com" target="_blank" class="me-3">
                <i class="fab fa-twitter fa-2x"></i>
              </a>
              <a href="https://instagram.com" target="_blank" class="me-3">
                <i class="fab fa-instagram fa-2x"></i>
              </a>
              <a href="https://linkedin.com" target="_blank" class="me-3">
                <i class="fab fa-linkedin fa-2x"></i>
              </a>
            </div>
          </div>
          <div class="col-md-4 mb-4">
            <h5 class="text-uppercase">Enlaces Útiles</h5>
            <ul class="list-unstyled">
              <li class="mb-2">
                <a href="#about" class="text-white">Sobre Nosotros</a>
              </li>
              <li class="mb-2">
                <a href="#services" class="text-white">Servicios</a>
              </li>
              <li class="mb-2">
                <a href="#contact" class="text-white">Contacto</a>
              </li>
              <li class="mb-2">
                <a href="#faq" class="text-white">Preguntas Frecuentes</a>
              </li>
            </ul>
          </div>
          <div class="col-md-4 mb-4">
            <h5 class="text-uppercase">Descarga el Juego</h5>
            <div class="mb-3">
              <a href="#register" class="btn btn-success btn-block">Regístrate</a>
            </div>
            <div>
              <a href="#login" class="btn btn-secondary btn-block">Iniciar Sesión</a>
            </div>
          </div>
        </div>
        <div class="row mt-4">
          <div class="col-12 text-center">
            <p class="mb-0">© 2024 Oliver Suárez. Todos los derechos reservados.</p>
          </div>
        </div>
      </div>
    </footer>
  </template>

  <script>
  export default {
    name: 'ComponentFooter'
  };
  </script>

  <style scoped>
  .footer {
    background-color: #2C3E50; /* Color de fondo oscuro */
    color: #ECF0F1; /* Texto en blanco */
    padding: 60px 0;
  }

  .footer h5 {
    color: #ECF0F1; /* Texto en blanco */
    margin-bottom: 1.5rem;
  }

  .footer p {
    color: #BDC3C7; /* Texto gris claro */
  }

  .footer a {
    color: #ECF0F1; /* Texto en blanco */
    text-decoration: none;
  }

  .footer a:hover {
    color: #2ECC71; /* Color verde claro al pasar el mouse */
  }

  .footer .social-icons a {
    color: #ECF0F1; /* Texto en blanco */
    transition: color 0.3s ease;
  }

  .footer .social-icons a:hover {
    color: #2ECC71; /* Color verde claro al pasar el mouse */
  }

  .btn-success {
    background-color: #2ECC71; /* Color verde claro */
    border-color: #2ECC71; /* Borde verde claro */
    color: #ECF0F1; /* Texto en blanco */
  }

  .btn-secondary {
    background-color: #E67E22; /* Color naranja */
    border-color: #E67E22; /* Borde naranja */
    color: #ECF0F1; /* Texto en blanco */
  }

  .btn-block {
    width: 100%;
  }
  </style>
