<template>
    <section class="download-section py-5">
      <div class="container">
        <h2 class="section-title text-center mb-5">Descarga Próximamente</h2>
        <div class="row">
          <div class="col-md-6">
            <div class="feature">
              <i class="fab fa-apple fa-5x mb-3 icon-ios"></i>
              <h4 class="mb-3">Disponible para iOS</h4>
              <p>Embárcate en una aventura épica desde tu dispositivo móvil Apple, explorando las leyendas y culturas de México.</p>
            </div>
          </div>
          <div class="col-md-6">
            <div class="feature">
              <i class="fab fa-android fa-5x mb-3 icon-android"></i>
              <h4 class="mb-3">Disponible para Android</h4>
              <p>Embárcate en una aventura épica desde tu dispositivo móvil Android, explorando las leyendas y culturas de México.</p>
            </div>
          </div>
          <div class="col-md-6 offset-md-3">
            <div class="feature">
              <i class="fab fa-windows fa-5x mb-3 icon-windows"></i>
              <h4 class="mb-3">Compatible con PC (Windows)</h4>
              <p>Vive la experiencia completa en tu computadora Windows, sumérgete en desafíos y descubre secretos ocultos.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>

  <script>
  export default {
    name: 'DownloadSection'
  }
  </script>

  <style scoped>
  .download-section {
    background-color: #000000; /* Fondo oscuro */
    color: #ffffff; /* Texto en blanco */
    padding: 60px 0;
  }

  .section-title {
    font-size: 2.8rem;
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #DAA520; /* Color dorado */
  }

  .feature {
    text-align: center;
    margin-bottom: 30px;
  }

  .icon-ios {
    color: #DAA520; /* Color dorado para iOS */
  }

  .icon-android {
    color: #3DDC84; /* Color verde para Android */
  }

  .icon-windows {
    color: #0078D7; /* Color azul para Windows */
  }

  h4 {
    font-size: 1.8rem;
    font-family: 'Cinzel', serif; /* Fuente elegante */
  }

  p {
    font-size: 1.125rem;
    line-height: 1.8;
  }
  </style>
