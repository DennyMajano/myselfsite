<template>
  <b-container fluid="lg" class="px-0">
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <b-nav-item href="#">DV-TECH</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
    <b-row no-gutters>
      <b-col>
        <b-card no-body class="overflow-hidden">
          <b-row no-gutters>
            <b-col md="6">
              <b-card-img
                src="../static/profile_picture.jpg"
                alt="Image"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col md="6">
              <b-card-body>
                <b-card-title>Denny José Vigil Majano</b-card-title>
                <b-card-sub-title>
                  <p>Egresado de Ingenieria en Sistemas y Redes Informáticas</p>
                </b-card-sub-title>
                <b-card-text>
                  <p class="font-italic">
                    "Soy una persona autodidacta con ganas de aprender y aplicar
                    los conocimientos en el mundo profesional."
                  </p>
                </b-card-text>
              </b-card-body>
              <!-- /b-card--->
              <!-- b-card--->
              <b-card-body>
                <b-card-sub-title> Tecnologías </b-card-sub-title>
                <b-card-text>
                  <b-badge variant="info">NodeJS</b-badge>
                  <b-badge variant="info">ReactJS</b-badge>
                  <b-badge variant="info">Nuxt</b-badge>
                </b-card-text>
              </b-card-body>
              <b-card-body>
                <b-card-sub-title class="mb-2">Contacto</b-card-sub-title>
                <b-card-text>
                  <b-list-group flush>
                    <b-list-group-item
                      ><b-icon
                        icon="envelope-fill"
                        class="mr-2"
                      />denny.majano@outlook.com</b-list-group-item
                    >
                    <b-list-group-item
                      ><b-icon icon="linkedin" class="mr-2" />
                      <a
                        href="https://www.linkedin.com/in/dennymajano/"
                        target="_blank"
                        >linkedin.com/in/dennymajano</a
                      ></b-list-group-item
                    >
                  </b-list-group>
                </b-card-text>
              </b-card-body>

              <b-card-body>
                <b-card-sub-title class="mb-2">Repositorios</b-card-sub-title>
                <b-card-text>
                  <b-list-group flush>
                    <b-list-group-item
                      ><b-icon icon="github" class="mr-2" /><a
                        href="https://github.com/DennyMajano"
                        >github.com/DennyMajano</a
                      ></b-list-group-item
                    >
                    <b-list-group-item
                      ><b-icon icon="github" class="mr-2" /><a
                        href="https://gitlab.com/DennyMajano"
                        >gitlab.com/DennyMajano</a
                      ></b-list-group-item
                    >
                  </b-list-group>
                </b-card-text>
              </b-card-body>
            </b-col>
          </b-row>
        </b-card>
      </b-col>
    </b-row>
    <b-row no-gutters>
      <b-col md="6">
        <b-card no-body>
          <b-card-body>
            <b-card-title>Estudios</b-card-title>
            <b-list-group flush>
              <b-list-group-item>
                <div>Ingeniería en Sistemas y Redes Informáticas</div>
                <div>Universidad Gerardo Barrios</div>
                <div>2016-2021</div>
              </b-list-group-item>
              <b-list-group-item>
                <div>Técnico Vocacional en Desarrollo de Software</div>
                <div>Instituto Nacional Isidro Menéndez</div>
                <div>2013-2025</div>
              </b-list-group-item>
            </b-list-group>
          </b-card-body>
        </b-card>
      </b-col>
      <b-col md="6">
        <b-card no-body>
          <b-card-body>
            <b-card-title>Habilidades</b-card-title>
            <b-list-group flush>
              <b-list-group-item>
                <div>Ingeniería en Sistemas y Redes Informáticas</div>
                <div>Universidad Gerardo Barrios</div>
                <div>2016-2021</div>
              </b-list-group-item>
              <b-list-group-item>
                <div>Técnico Vocacional en Desarrollo de Software</div>
                <div>Instituto Nacional Isidro Menéndez</div>
                <div>2013-2025</div>
              </b-list-group-item>
            </b-list-group>
          </b-card-body>
        </b-card>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'Normal',
}
</script>
<style></style>
