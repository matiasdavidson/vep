<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">Veganismo en Parques</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#about">Qué hacemos</a>
            </li>
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#participar">Cómo participar</a>
            </li>
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#portfolio">Material</a>
            </li>
            <li class="nav-item">
              <a target="_blank" class="nav-link js-scroll-trigger" href="https://docs.google.com/forms/d/e/1FAIpQLSejkhGf3g2TvVt5ckGjFqbUE5R_LHWK7uscc7lCG7JgvO11Xw/viewform">Inscribite!</a>
            </li>
            <a style="align-self:center" target="_blank" href="https://www.instagram.com/veganismoenparques/"><img class="header-icon" src="../src/assets/img/instagram-logo.png" alt=""></a>
            <a style="align-self:center" target="_blank" href="https://linktr.ee/veganismoenparques"><img class="header-icon" src="../src/assets/img/books-icon.png" alt=""></a>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Les damos la bienvenida a Veganismo en Parques!</div>
          <div class="intro-heading">Activismo autogestivo y descentralizado por los derechos animales.</div>
          <img src="./assets/img/scroll.png" alt="scroll" class="scroll-icon">
        </div>
      </div>
    </header>

    <!-- About -->
    <section id="about">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Qué hacemos</h2>
            <h3 class="section-subheading text-muted"></h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12 text-center">
            <h3 class="section-subheading text-muted about-text">Somos un grupo de activistas que se maneja de manera descentralizada y autogestiva. <br> <br>¿Qué quiere decir? Como organización, lo que hacemos es brindar un marco para que los activistas puedan gestionar sus propios grupos y momentos de activismo. Por medio de un formulario de inscripción, unimos activistas que se muevan por las mismas zonas, para que puedan activar en conjunto. Para esto, armamos grupos de Whatsapp por zona.<br><br>
            También ofrecemos a quienes activan material para formarse en derechos animales como videos, textos, documentales, libros y talleres. Nos parece esencial para poder activar con las herramientas adecuadas, que toda persona que luche por los derechos animales esté formada en la materia. La teoría es muy importante a la hora de activar.<br><br>
            Por último, ofrecemos también material útil para el activismo (folletos, videos y banners) para que puedan imprimir y llevar a los activismos.
            <br><br>
            La idea es tener un activismo con personas formadas y que toda persona que quiera activar, pueda hacerlo sin depender de días y horarios fijos o de que una organización esté o no presente en su ciudad. Los días, horarios y lugar de los activismos los maneja cada grupo y si no conocés ninguna organización en tu zona, podés anotarte y buscaremos personas que se hayan anotado, que estén cercanas a vos.
            <br><br>
            </h3>
          </div>
          <div class="languages col-lg-12 text-center">
            <img class="language-flag" src="./assets/img/activando2.png" alt="Spanish" title="">
            <img class="language-flag" src="./assets/img/activando3.png" alt="English" title="">
            <img class="language-flag" src="./assets/img/activando4.png" alt="Hebrew" title="">
            <img class="language-flag" src="./assets/img/activando5.png" alt="Portuguese" title="">
            <img class="language-flag" src="./assets/img/activando6.png" alt="Portuguese" title="">
            <img class="language-flag" src="./assets/img/activando7.png" alt="Portuguese" title="">
          </div>
        </div>
      </div>
    </section>

    <!-- Como participar -->
    <section id="participar" class="bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Cómo participar</h2>
            <h3 class="section-subheading text-muted"></h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <ul class="timeline">
              <li>
                <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSejkhGf3g2TvVt5ckGjFqbUE5R_LHWK7uscc7lCG7JgvO11Xw/viewform"><div class="timeline-image timeline-image1">
                  <img class="rounded-circle img-fluid" src="" alt="">
                </div></a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>Paso 1</h4>
                    <h4 class="subheading">Inscribite</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Presionando <a href="https://docs.google.com/forms/d/e/1FAIpQLSejkhGf3g2TvVt5ckGjFqbUE5R_LHWK7uscc7lCG7JgvO11Xw/viewform">aquí</a>, accedés al formulario de inscripción.</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <a target="_blank" href="https://linktr.ee/veganismoenparques">
                  <div class="timeline-image timeline-image2">
                  <img class="rounded-circle img-fluid" src="img/about/2.jpg" alt="">
                </div> </a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>Paso 2</h4>
                    <h4 class="subheading">Aprendamos acerca de derechos animales</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Para poder ser eficientes en nuestro activismo, es necesario que nos formemos. Para eso, tenemos mucha información, libros, textos, talleres y videos para contar con herramientas para el activismo. Hacé click <a href="https://linktr.ee/veganismoenparques">aquí</a> para ver el material.</p>
                  </div>
                </div>
              </li>
              <li>
                <a target="_blank" href="https://www.instagram.com/veganismoenparques/">                
                <div class="timeline-image timeline-image3">
                  <img class="rounded-circle img-fluid" src="img/about/3.jpg" alt="">
                </div></a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>Paso 3</h4>
                    <h4 class="subheading">Te sumamos a un grupo!</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Una vez que recibimos tu inscripción, buscaremos activistas que se muevan por la misma zona que vos para que puedan formar un grupo (o sumarte a uno formado) y que puedas activar allí. Te sumaremos al grupo de Whatsapp y podés arrancar a activar!</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <a target="_blank" href="https://www.instagram.com/veganismoenparques/">       
                <div class="timeline-image timeline-image4">
                  <img class="rounded-circle img-fluid" src="img/about/4.jpg" alt="">
                </div></a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>Paso 4</h4>
                    <h4 class="subheading">Constancia</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Te ayudaremos a mantenerte con información certera por medio de talleres, documentales, textos y videos. Te toca a vos mantener el activismo saliendo siempre que puedas!</p>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio Grid -->
    <Portfolio></Portfolio>

    <!-- Footer -->
    <footer style="background-color: black">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Veganismo en Parques</span>
          </div>
          <div class="col-md-4">
            <span class="copyright">veganismoenparques@gmail.com</span>
          </div>
          <div class="col-md-4">
            <a style="align-self:center" target="_blank" href="https://www.instagram.com/veganismoenparques/"><img class="header-icon footer-icon" src="../src/assets/img/instagram-logo.png" alt=""></a>
            <a style="align-self:center" target="_blank" href="https://linktr.ee/veganismoenparques"><img class="header-icon footer-icon" src="../src/assets/img/books-icon.png" alt=""></a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  methods: {
    collapseMenu: function(event){
      document.getElementById("navbarResponsive").classList.remove("show");
    }
  },
  components: {
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
