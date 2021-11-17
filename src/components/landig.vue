<template>
  <div>
     <header class="headerr vh-100">
        <div class="container d-flex flex-column h-100 justify-content-between px-2">
            <div class="d-flex justify-content-between align-items-center pt-3">
                <a href="index.html"><img src="../assets/img/logo.svg" alt="logo" /></a>

                <nav>
                    <a class="text-decoration-none text-white fs-2 me-1" href="#nosotros">Nosotros</a>
                    <a class="text-decoration-none text-white fs-2 me-1" href="#">Anuncios</a>
                    <a class="text-decoration-none text-white fs-2 me-1" href="#">Blog</a>
                    <a class="text-decoration-none text-white fs-2 me-1" href="#">contacto</a>
                </nav>
            </div>

            <h1 class="text-white pb-2 fs-4 lh-sm title-home">Venta de Casa y Departamentos Exclusivos de Lujos</h1>
        </div>
    </header>

    <section id="nosotros" class="container my-2 px-2">
        <h2 class="text-center fw-300 mb-3 fs-3">Mas Sobre Nosotros</h2>

        <div class="row row-cols-xs-1 row-cols-sm-2 row-cols-md-3 justify-content-center">
            <div class="text-center lh-lg px-2 py-3">
                <img class="pb-2" src="../assets/img/icono1.svg" alt="icono de seguridad" />
                <h3 class="text-uppercase fs-2">seguridad</h3>
                <p class="fs-1c5">
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Praesentium nostrum tempora omnis accusantium alias pariatur voluptatem placeat! Incidunt odit aspernatur numquam dolorum possimus, tenetur fugiat minima sed dolores reiciendis aperiam.
                </p>
            </div>

            <div class="text-center lh-lg px-2 py-3">
                <img class="pb-2" src="../assets/img/icono2.svg" alt="icono de mejor a tiempo" />
                <h3 class="text-uppercase fs-2">el mejor precio</h3>
                <p class="fs-1c5">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae illo blanditiis, quas facilis illum eligendi laudantium earum dolorem repudiandae dicta
                </p>
            </div>

            <div class="text-center lh-lg px-2 py-3">
                <img class="pb-2" src="../assets/img/icono3.svg" alt="icono de a tiempo" />
                <h3 class="text-uppercase fs-2">a tiempo</h3>
                <p class="fs-1c5">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae illo blanditiis, quas facilis illum eligendi laudantium earum dolorem repudiandae dicta
                </p>
            </div>
        </div>
    </section>

    <section class="home-contacto align-items-center d-flex px-2">
        <div class="container contenedor-contacto text-white">
            <h2 class="fs-3">Encuentra la Casa de tus Sueños</h2>
            <p class="fs-2 mb-4 fw-bold">llena el formulario de contacto y un asesor se pondra en contacto contigo a la brevedad</p>
            <a class="boton btn-contacto" href="#">contactanos</a>
        </div>
    </section>
    <div class="container pt-3 px-2">
        <div class="row row-cols-xs-1 row-cols-sm-1 row-cols-md-1 row-cols-lg-2">
            <section class="py-3 col-lg-7">
                <h3 class="fw-300 text-center fs-3">Nuestro Blog</h3>

                <div class="row">
                    <article class="px-2 px-sm-0 my-2 b-radius c-card col-12">
                        <div class="row row-cols-xs-1 row-cols-sm-2 m-1">
                            <div class="pe-1c5 py-2 d-flex align-items-center col-sm-5">
                                <img class="border border-white" src="../assets/img/blog1.jpg" alt="" />
                            </div>
                            <div class="col-sm-7">
                                <h4 class="text-white fs-2 fw-bold">Terraza en el Techo de tu Casa</h4>
                                <p class="text-white fs-1c5">
                                    Escrito el: <span class="text-color"> 26/09/2021</span> <br /> por: <span class="text-color"> Admin</span>
                                </p>
                                <p class="text-white fs-1c5">
                                    consejos para construir una terraza en el techo de tu casa, con los mejore materiales ahorrando dinero.
                                </p>
                            </div>
                        </div>
                    </article>

                    <article class="px-2 px-sm-0 my-2 b-radius c-card col-12">
                        <div class="row row-cols-xs-1 row-cols-sm-2 m-1">
                            <div class="cpe-1c5 py-2 d-flex align-items-center col-sm-5">
                                <img class="border border-white" src="../assets/img/blog2.jpg" alt="" />
                            </div>
                            <div class="col-sm-7">
                                <h4 class="text-white fs-2 fw-bold">Guia para la Decoracion de tu Hogar</h4>
                                <p class="text-white fs-1c5">
                                    Escrito el: <span class="text-color"> 26/09/2021</span> <br /> por: <span class="text-color"> Admin</span>
                                </p>
                                <p class="text-white fs-1c5">
                                    maximiza el espacio en tu hogar con esta guia, aprende a combinar muebles y colore para darle vida a tu espacio
                                </p>
                            </div>
                        </div>
                    </article>
                </div>
            </section>

            <section class="pb-3 col-lg-5 ps-lg-2">
                <h3 class="fw-300 text-center">Testimoniales</h3>
                <div class="testimonial fs-2c5 mt-2 text-white p-2">
                    <blockquote class="fw-300 position-relative ps-5">
                        El personal se comporto de una excelente manera, muy buena atencion y la casa que me ofrecieron cumple con todas mis expectativas
                    </blockquote>

                    <p class="text-end fs-1c5 mt-2 text-white">- Duver H. Cobos</p>
                </div>
            </section>
        </div>
    </div>
    <footer class="site-footer px-2">
        <div class="container pt-3 pb-3 d-flex justify-content-between align-items-center">
            <nav>
                <a class="text-decoration-none text-white fs-1c5 me-1" href="#">Nosotros</a>
                <a class="text-decoration-none text-white fs-1c5 me-1" href="#">Anuncios</a>
                <a class="text-decoration-none text-white fs-1c5 me-1" href="#">Blog</a>
                <a class="text-decoration-none text-white fs-1c5 me-1" href="#">contacto</a>
            </nav>

            <p class="text-white fs-1c5 m-0">Todos los Derechos Reservados 2021 &copy;</p>
        </div>
    </footer>
  </div>
</template>

<script>

export default {
  name: 'landing',
  components: {
    
  }
}
</script>

<style>
html {
  font-size: 62.5%;
  /*reset para rems -62.5 = 10px de 16px */
}

img {
  max-width: 100%;
}

.headerr {
  
  background-image: url(../assets/img/header.jpg);
  background-position: center center;
  background-size: cover;
  min-height: 60rem;
}

.title-home {
  max-width: 60rem;
  letter-spacing: 2px;
}

.fw-300 {
  font-weight: 300;
}

.home-contacto {
  background-image: url(../assets/img/encuentra.jpg);
  height: 40rem;
  background-position: center center;
  background-size: cover;
}

.boton {
  border: 2px solid #1c8872;
  padding: 1rem 3rem;
  text-decoration: none;
  font-weight: 700;
  text-transform: uppercase;
  font-size: 1.5rem;
  margin-top: 2rem;
  text-align: center;
  -webkit-transition: color 0.5s, background 0.5s;
  transition: color 0.5s, background 0.5s;
  border-radius: 4rem;
}

.btn-contacto {
  background-color: #1c8872;
  color: white;
}

.btn-contacto:hover {
  background-color: transparent;
  color: white;
  border: 2px solid white;
}

.c-card {
  background-color: #192229;
}

.text-color {
  color: #1c8872;
}

.b-radius {
  border-radius: 1rem;
}

.testimonial {
  background-color: #1c8872;
  border-radius: 2rem;
}

.testimonial blockquote::before {
  content: '';
  background-image: url(../assets/img/comilla.svg);
  width: 4rem;
  height: 4rem;
  padding: 2rem;
  position: absolute;
  background-position: center center;
  background-size: cover;
  left: -1rem;
}

.site-footer {
  background-color: #192229;
  margin: 0;
}

/*!
 * Bootstrap v5.0.0-beta3 (https://getbootstrap.com/)
 * Copyright 2011-2021 The Bootstrap Authors
 * Copyright 2011-2021 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/main/LICENSE)
 */
:root {
  --bs-blue: #0d6efd;
  --bs-indigo: #6610f2;
  --bs-purple: #6f42c1;
  --bs-pink: #d63384;
  --bs-red: #dc3545;
  --bs-orange: #fd7e14;
  --bs-yellow: #ffc107;
  --bs-green: #198754;
  --bs-teal: #20c997;
  --bs-cyan: #0dcaf0;
  --bs-white: #fff;
  --bs-gray: #6c757d;
  --bs-gray-dark: #343a40;
  --bs-primary: #0d6efd;
  --bs-secondary: #6c757d;
  --bs-success: #198754;
  --bs-info: #0dcaf0;
  --bs-warning: #ffc107;
  --bs-danger: #dc3545;
  --bs-light: #f8f9fa;
  --bs-dark: #212529;
  --bs-font-sans-serif: "Lato", sans-serif;
  --bs-font-monospace: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  --bs-gradient: linear-gradient(180deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0));
}

*,
*::before,
*::after {
  -webkit-box-sizing: border-box;
          box-sizing: border-box;
}

@media (prefers-reduced-motion: no-preference) {
  :root {
    scroll-behavior: smooth;
  }
}

body {
  margin: 0;
  font-family: var(--bs-font-sans-serif);
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
  -webkit-text-size-adjust: 100%;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

h1, .h1, h2, .h2, h3, .h3, h4, .h4 {
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-weight: 500;
  line-height: 1.2;
}

h1, .h1 {
  font-size: 1rem;
}

h2, .h2 {
  font-size: calc(1.325rem + 0.9vw);
}

@media (min-width: 1200px) {
  h2, .h2 {
    font-size: 2rem;
  }
}

h3, .h3 {
  font-size: calc(1.425rem + 2.1vw);
}

@media (min-width: 1200px) {
  h3, .h3 {
    font-size: 3rem;
  }
}

h4, .h4 {
  font-size: calc(1.525rem + 3.3vw);
}

@media (min-width: 1200px) {
  h4, .h4 {
    font-size: 4rem;
  }
}

p {
  margin-top: 0;
  margin-bottom: 1rem;
}

blockquote {
  margin: 0 0 1rem;
}

a {
  color: #0d6efd;
  text-decoration: underline;
}

a:hover {
  color: #0a58ca;
}

a:not([href]):not([class]), a:not([href]):not([class]):hover {
  color: inherit;
  text-decoration: none;
}

img,
svg {
  vertical-align: middle;
}

/* rtl:raw:
[type="tel"],
[type="url"],
[type="email"],
[type="number"] {
  direction: ltr;
}
*/

.blockquote {
  margin-bottom: 1rem;
  font-size: 1.25rem;
}

.blockquote > :last-child {
  margin-bottom: 0;
}

.container {
  width: 100%;
  padding-right: var(--bs-gutter-x, 0.5rem);
  padding-left: var(--bs-gutter-x, 0.5rem);
  margin-right: auto;
  margin-left: auto;
}

@media (min-width: 576px) {
  .container {
    max-width: 90%;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 90%;
  }
}

@media (min-width: 992px) {
  .container {
    max-width: 90%;
  }
}

@media (min-width: 1200px) {
  .container {
    max-width: 90%;
  }
}

@media (min-width: 1400px) {
  .container {
    max-width: 90%;
  }
}

.row {
  --bs-gutter-x: 1rem;
  --bs-gutter-y: 0;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
  margin-top: calc(var(--bs-gutter-y) * -1);
  margin-right: calc(var(--bs-gutter-x) / -2);
  margin-left: calc(var(--bs-gutter-x) / -2);
}

.row > * {
  -ms-flex-negative: 0;
      flex-shrink: 0;
  width: 100%;
  max-width: 100%;
  padding-right: calc(var(--bs-gutter-x) / 2);
  padding-left: calc(var(--bs-gutter-x) / 2);
  margin-top: var(--bs-gutter-y);
}

.col-12 {
  -webkit-box-flex: 0;
      -ms-flex: 0 0 auto;
          flex: 0 0 auto;
  width: 100%;
}

@media (min-width: 576px) {
  .row-cols-sm-1 > * {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 100%;
  }
  .row-cols-sm-2 > * {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 50%;
  }
  .col-sm-5 {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 41.66667%;
  }
  .col-sm-7 {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 58.33333%;
  }
}

@media (min-width: 768px) {
  .row-cols-md-1 > * {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 100%;
  }
  .row-cols-md-3 > * {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 33.33333%;
  }
}

@media (min-width: 992px) {
  .row-cols-lg-2 > * {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 50%;
  }
  .col-lg-5 {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 41.66667%;
  }
  .col-lg-7 {
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
    width: 58.33333%;
  }
}

.nav {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}

@keyframes progress-bar-stripes {
  0% {
    background-position-x: 1rem;
  }
}

/* rtl:begin:ignore */

/* rtl:end:ignore */

/* rtl:options: {
  "autoRename": true,
  "stringMap":[ {
    "name"    : "prev-next",
    "search"  : "prev",
    "replace" : "next"
  } ]
} */

@keyframes spinner-border {
  to {
    -webkit-transform: rotate(360deg) /* rtl:ignore */;
            transform: rotate(360deg) /* rtl:ignore */;
  }
}

@keyframes spinner-grow {
  0% {
    -webkit-transform: scale(0);
            transform: scale(0);
  }
  50% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.d-flex {
  display: -webkit-box !important;
  display: -ms-flexbox !important;
  display: flex !important;
}

.position-relative {
  position: relative !important;
}

.border {
  border: 1px solid #dee2e6 !important;
}

.border-white {
  border-color: #fff !important;
}

.h-100 {
  height: 100% !important;
}

.vh-100 {
  height: 100vh !important;
}

.flex-column {
  -webkit-box-orient: vertical !important;
  -webkit-box-direction: normal !important;
      -ms-flex-direction: column !important;
          flex-direction: column !important;
}

.justify-content-center {
  -webkit-box-pack: center !important;
      -ms-flex-pack: center !important;
          justify-content: center !important;
}

.justify-content-between {
  -webkit-box-pack: justify !important;
      -ms-flex-pack: justify !important;
          justify-content: space-between !important;
}

.align-items-center {
  -webkit-box-align: center !important;
      -ms-flex-align: center !important;
          align-items: center !important;
}

.m-0 {
  margin: 0 !important;
}

.m-1 {
  margin: 1rem !important;
}

.my-2 {
  margin-top: 2rem !important;
  margin-bottom: 2rem !important;
}

.mt-2 {
  margin-top: 2rem !important;
}

.me-1 {
  margin-right: 1rem !important;
}

.mb-3 {
  margin-bottom: 3rem !important;
}

.mb-4 {
  margin-bottom: 4rem !important;
}

.p-2 {
  padding: 2rem !important;
}

.px-2 {
  padding-right: 2rem !important;
  padding-left: 2rem !important;
}

.py-2 {
  padding-top: 2rem !important;
  padding-bottom: 2rem !important;
}

.py-3 {
  padding-top: 3rem !important;
  padding-bottom: 3rem !important;
}

.pt-3 {
  padding-top: 3rem !important;
}

.pe-1c5 {
  padding-right: 1.5rem !important;
}

.pb-2 {
  padding-bottom: 2rem !important;
}

.pb-3 {
  padding-bottom: 3rem !important;
}

.ps-5 {
  padding-left: 5rem !important;
}

.fs-1c5 {
  font-size: calc(1.275rem + 0.3vw) !important;
}

.fs-2 {
  font-size: calc(1.325rem + 0.9vw) !important;
}

.fs-2c5 {
  font-size: calc(1.375rem + 1.5vw) !important;
}

.fs-3 {
  font-size: calc(1.425rem + 2.1vw) !important;
}

.fs-4 {
  font-size: calc(1.525rem + 3.3vw) !important;
}

.fw-bold {
  font-weight: 700 !important;
}

.lh-sm {
  line-height: 1.25 !important;
}

.lh-lg {
  line-height: 2 !important;
}

.text-end {
  text-align: right !important;
}

.text-center {
  text-align: center !important;
}

.text-decoration-none {
  text-decoration: none !important;
}

.text-uppercase {
  text-transform: uppercase !important;
}

/* rtl:begin:remove */

/* rtl:end:remove */

.text-white {
  color: #fff !important;
}

@media (min-width: 576px) {
  .px-sm-0 {
    padding-right: 0 !important;
    padding-left: 0 !important;
  }
}

@media (min-width: 992px) {
  .ps-lg-2 {
    padding-left: 2rem !important;
  }
}

@media (min-width: 1200px) {
  .fs-1c5 {
    font-size: 1.5rem !important;
  }
  .fs-2 {
    font-size: 2rem !important;
  }
  .fs-2c5 {
    font-size: 2.5rem !important;
  }
  .fs-3 {
    font-size: 3rem !important;
  }
  .fs-4 {
    font-size: 4rem !important;
  }
}
</style>
