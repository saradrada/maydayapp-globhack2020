<template>
  <div>

    
    <div class="position-relative">
      <section class="section-shaped my-0">
        <div class="shape shape-style-1 bg-gradient-info shape-skew">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="container shape-container d-flex">
          <div class="col px-0">
            <div class="row">
              <div class="col-lg-6">

                <h1 class="display-3 text-white">Una aplicación especial para la oferta de ayudas</h1>
                <p
                  class="lead text-white"
                >Esta pagina web te dara la capacidad de ofrecer y recibir ayudas a personas y empresas afectadas por el COVID-19, tanto para personas como para empresas se han definido diferentes ayudas.</p>
                <div class="btn-wrapper"></div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 1st Hero Variation -->
    </div>
    
    <section class="section section-lg pt-lg-0 mt--200">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-12">
            <div class="row row-grid">
              <div class="col-lg-4">
                <card class="border-0 text-center" hover shadow body-classes="py-5">
                  <img src="img/helps/people.jpg" alt="people" border="0" style="height: 180px;" />
                  <h6 class="text-primary text-uppercase">Personas</h6>
                  <p class="description mt-3">
                    Aquí podrás encontrar información sobre diferentes tipos de
                    ayudas para personas.
                  </p>
                  <div>
                    <badge type="primary" rounded>MÉDICA</badge>
                    <badge type="primary" rounded>TRABAJO</badge>
                    <badge type="primary" rounded>HUMANITARIA</badge>
                    <badge type="primary" rounded>PSICOLÓGICA</badge>
                  </div>

                <base-button type="primary" class="mt-4">
                    <router-link to="/helpMenu" style="color:white">Entrar</router-link>
                  </base-button>
               
               
                </card>
              </div>
              <div class="col-lg-4">
                <card class="border-0 text-center" hover shadow body-classes="py-5">
                  <img src="img/helps/work2.jpg" alt="work" border="0" style="height: 180px;" />

                  <h6 class="text-info text-uppercase">Empresas</h6>
                  <p class="description mt-3">
                    Aquí podrás encontrar información sobre diferentes tipos de
                    ayudas para empresas.
                  </p>
                  <div>
                    <badge type="info" rounded>BIOSEGURIDAD</badge>
                    <badge type="info" rounded>EMPRENDIMIENTO</badge>
                    <badge type="info" rounded>AYUDA DEL ESTADO</badge>
                    <badge type="info" rounded></badge>
                  </div>
                  <base-button tag="a" href="#" type="info" class="mt-4">Entrar</base-button>
                </card>
              </div>

              <div class="col-lg-4">
                <card class="border-0 text-center" hover shadow body-classes="py-5">
                  <img
                    src="img/helps/other.png"
                    class="text-center"
                    alt="work"
                    border="0"
                    style="height: 180px;"
                  />
                  <h6 class="text-success text-uppercase" align>Otras Ayudas</h6>
                  <p class="description mt-3">
                    Aquí podrás encontrar información sobre cualquier otro tipo
                    ayuda.
                  </p>
                  <div>
                    <badge type="success" rounded>LEGALES</badge>
                    <badge type="success" rounded>CONTÁCTANOS</badge>
                    <badge type="success" rounded>PERSONAS ESPECIALES</badge>
                    <badge type="success" rounded></badge>
                  </div>
                  <base-button
                    tag="a"
                    href="#"
                    type="success"
                    class="mt-4 justify-content-center"
                  >Entrar</base-button>
                </card>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>

  
</template>

<script>
export default {
<<<<<<< HEAD
  name: '',
  components: {
  }
}
=======
  name: "home",
  components: {}
};
>>>>>>> 5d476bdf570bdf8e17b5c1b330bab8a84a4b1586
</script>
