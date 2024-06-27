<template>
    <section class="contact py-5">
      <div class="container">
        <h2 class="section-title text-center mb-5">Contacto</h2>
        <div class="row">
          <div class="col-md-6">
            <h4 class="mb-4">Ponte en Contacto</h4>
            <p class="mb-4">
              Si tienes alguna pregunta o necesitas más información, no dudes en contactarnos a través de cualquiera de los siguientes métodos:
            </p>
            <ul class="list-unstyled">
              <li class="mb-3">
                <i class="fas fa-phone-alt fa-2x text-success me-3"></i>
                <span>(123) 456-7890</span>
              </li>
              <li class="mb-3">
                <i class="fas fa-envelope fa-2x text-success me-3"></i>
                <span>info@tesoroazteca.com</span>
              </li>
              <li class="mb-3">
                <i class="fas fa-map-marker-alt fa-2x text-success me-3"></i>
                <span>Av. Universidad Tecnológica 200, Ciudad Bajío, 36766 Salamanca, Gto.</span>
              </li>
            </ul>
          </div>
          <div class="col-md-6">
            <div class="map-responsive">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3735.2748349096146!2d-101.23508392394626!3d20.576831003145802!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x842c85c965f8dd99%3A0xf0c50b96a2552383!2sUniversidad%20Tecnol%C3%B3gica%20de%20Salamanca!5e0!3m2!1ses-419!2smx!4v1717780486982!5m2!1ses-419!2smx"
                width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>

  <script>
  export default {
    name: 'SectionContact'
  };
  </script>

  <style scoped>
  .contact {
    background-color: #333333 !important; /* Color de fondo oscuro */
    color: #ffffff; /* Texto en blanco */
    padding: 60px 0;
  }

  .section-title {
    font-size: 2.8rem;
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #DAA520; /* Color dorado */
  }

  h4 {
    font-size: 1.8rem;
    font-family: 'Cinzel', serif; /* Fuente elegante */
    color: #ffffff; /* Texto en blanco */
  }

  p,
  span {
    font-size: 1.1rem;
  }

  i {
    color: #2ECC71; /* Color verde claro */
  }

  ul {
    padding-left: 0;
  }

  ul li {
    display: flex;
    align-items: center;
  }

  ul li i {
    transition: transform 0.3s ease;
  }

  ul li i:hover {
    transform: scale(1.1);
  }

  @media (max-width: 768px) {
    .row {
      flex-direction: column;
    }

    .col-md-6 {
      width: 100%;
      margin-bottom: 2rem;
    }

    ul {
      text-align: left;
    }

    ul li {
      justify-content: center;
    }
  }

  .map-responsive {
    overflow: hidden;
    padding-bottom: 56.25%; /* Proporción del video (16:9) */
    position: relative;
    height: 0;
  }

  .map-responsive iframe {
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    position: absolute;
  }
  </style>
