<template>
  <b-container fluid="lg" class="px-0">
    <b-navbar type="dark" variant="dark">
      <b-navbar-brand>
        DV-TECH
      </b-navbar-brand>
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
                  <span class="font-italic">
                    "Me gusta aprender de todo un poco y aplicar estos
                    conocimientos en el ámbito profesional"
                  </span>
                </b-card-text>
              </b-card-body>
              <!-- /b-card--->
              <!-- b-card--->
              <b-card-body>
                <b-card-sub-title> Hobbies</b-card-sub-title>
                <b-card-text>
                  <b-badge variant="info">Unity engine</b-badge>
                </b-card-text>
              </b-card-body>
              <b-card-body>
                <b-card-sub-title> Tecnologías</b-card-sub-title>
                <b-card-text>
                  <b-badge variant="info">NodeJS</b-badge>
                  <b-badge variant="info">ReactJS</b-badge>
                  <b-badge variant="info">Nuxt</b-badge>
                  <b-badge variant="info">MariaDB</b-badge>
                  <b-badge variant="info">Firebase</b-badge>
                </b-card-text>
              </b-card-body>
              <b-card-body>
                <b-card-sub-title> Idiomas </b-card-sub-title>
                <b-card-text>
                  <b-badge variant="info">Español nativo</b-badge>
                  <b-badge variant="info">Inglés básico/medio</b-badge>
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
        <b-card no-body class="h-100">
          <b-card-body>
            <b-card-title>Formación Académica</b-card-title>
            <b-list-group flush>
              <b-list-group-item>
                <h5>Ingeniería en Sistemas y Redes Informáticas</h5>
                <div>Universidad Gerardo Barrios</div>
                <div>2016-2021</div>
                <div>
                  <b-badge variant="secondary"
                    ><b-icon icon="star-fill" /> Coeficiente de Unidades de
                    Mérito: 9.4</b-badge
                  >
                </div>
              </b-list-group-item>
              <b-list-group-item>
                <h5>Técnico Vocacional en Desarrollo de Software</h5>
                <div>Instituto Nacional Isidro Menéndez</div>
                <div>2013-2015</div>
                <div>
                  <b-badge variant="secondary">
                    <b-icon icon="award-fill" />Excelencia Académica de la
                    promoción</b-badge
                  >
                </div>
              </b-list-group-item>
            </b-list-group>
          </b-card-body>
        </b-card>
      </b-col>
      <b-col md="6">
        <b-card no-body class="h-100">
          <b-card-body>
            <b-card-title>Proyectos Académicos y colaborativos</b-card-title>
            <b-list-group flush>
              <b-list-group-item>
                SOFTWARE DE REPORTE CIUDADANO
              </b-list-group-item>
              <b-list-group-item>
                PLATAFORMA BIBLIOTECH (BUSCADOR DECONTENIDO)
              </b-list-group-item>
              <b-list-group-item>
                SOFTWARE DE ADMINISTRACIÓN DE PAQUETERIA (Viajeros)
              </b-list-group-item>
              <b-list-group-item>
                SOFTWARE DE ADMINISTRACIÓN DE IGLESIA
              </b-list-group-item>
            </b-list-group>
          </b-card-body>
        </b-card>
      </b-col>
    </b-row>
    <b-row no-gutters>
      <b-col md="6">
        <b-card no-body class="h-100">
          <b-card-body>
            <b-card-title>Certificaciones</b-card-title>
            <b-list-group flush>
              <b-list-group-item>
                Cisco IT Essentials: PC Hardware and Software
              </b-list-group-item>
              <b-list-group-item>
                Cisco CCNA R&S: Introduction to Networks
              </b-list-group-item>
              <b-list-group-item>
                Cisco CCNA R&S: Routing and Switching Essentials
              </b-list-group-item>
              <b-list-group-item>
                Cisco CCNA R&S: Connecting Networks
              </b-list-group-item>
              <b-list-group-item>
                Cisco CCNA R&S: Scaling Networks
              </b-list-group-item>
            </b-list-group>
          </b-card-body>
        </b-card>
      </b-col>
      <b-col md="6">
        <b-card no-body class="h-100">
          <b-card-body>
            <b-card-title>Otros conocimientos</b-card-title>
            <b-badge variant="secondary">Ubuntu </b-badge>
            <b-badge variant="secondary">VS Code </b-badge>
            <b-badge variant="secondary">Android Studio - Java </b-badge>
            <b-badge variant="secondary">Bootstrap </b-badge>
            <b-badge variant="secondary">VMWare </b-badge>
            <b-badge variant="secondary">Git </b-badge>
            <b-badge variant="secondary">PHP </b-badge>
            <b-badge variant="secondary">Express JS </b-badge>
            <b-badge variant="secondary">C# </b-badge>
            <b-badge variant="secondary">.Net Básico</b-badge>
            <b-badge variant="secondary">Microsoft Visual Studio</b-badge>
            <b-badge variant="secondary">Unity</b-badge>
            <b-badge variant="secondary">Paint.net</b-badge>
            <b-badge variant="secondary">Blender</b-badge>
            <b-badge variant="secondary">MongoDB</b-badge>
            <b-badge variant="secondary">Slim Framework</b-badge>
            <b-badge variant="secondary">Angular</b-badge>
            <b-badge variant="secondary">SQL Server básico</b-badge>
            
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
