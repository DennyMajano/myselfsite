<template>
  <fragment>
    <b-row>
      <b-col>
        <b-card no-body class="p-2" style="max-width: 100%">
          <b-row>
            <!-- Lado izquierdo  -->
            <b-col md="4" class="border-right pr-4 pl-4">
              <div class="text-center">
                <b-card-img
                  src="../static/profile.png"
                  alt="Image"
                  class="rounded-0"
                  style="height: 12rem; width: auto"
                  center
                ></b-card-img>
              </div>
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
              <hr />
              <b-card-sub-title class="mb-2">Contacto</b-card-sub-title>
              <b-card-text>
                <ul class="list-unstyled">
                  <li>
                    <b-icon
                      icon="envelope-fill"
                      class="mr-2"
                    />denny.majano@outlook.com
                  </li>
                  <li>
                    <b-icon icon="linkedin" class="mr-2" /><a
                      href="https://www.linkedin.com/in/dennymajano/"
                      target="_blank"
                      >linkedin.com/in/dennymajano</a
                    >
                  </li>
                  <li></li>
                </ul>
              </b-card-text>
              <hr/>
              <b-card-sub-title class="mb-2">Repositorios</b-card-sub-title>
              <b-card-text>
                <ul class="list-unstyled">
                  <li>
                    <b-icon icon="github" class="mr-2" /><a
                      href="https://github.com/DennyMajano"
                      >github.com/DennyMajano</a
                    >
                  </li>
                  <li>
                    <b-icon icon="github" class="mr-2" /><a
                      href="https://gitlab.com/DennyMajano"
                      >gitlab.com/DennyMajano</a
                    >
                  </li>
                </ul>
              </b-card-text>

              <!-- Idiomas -->
              <hr />
              <b-card-sub-title> Idiomas </b-card-sub-title>
              <b-card-text>
                <b-badge variant="info">Español nativo</b-badge>
                <b-badge variant="info">Inglés básico/medio</b-badge>
              </b-card-text>
              <!-- /Idiomas -->
              <!-- Hobbies -->
              <hr />
              <b-card-sub-title> Hobbies</b-card-sub-title>
              <b-card-text>
                <b-badge variant="info">Crear juegos indies</b-badge>
              </b-card-text>
              <!-- /Hobbies -->
              <!-- Otros Conocimiento -->
              <hr/>
              <b-card-sub-title>Otros conocimientos / usados</b-card-sub-title>
              <b-badge variant="secondary">Ubuntu</b-badge>
              <b-badge variant="secondary">VS Code</b-badge>
              <b-badge variant="secondary">Android Studio - Java</b-badge>
              <b-badge variant="secondary">Bootstrap</b-badge>
              <b-badge variant="secondary">VMWare</b-badge>
              <b-badge variant="secondary">Virtual Box</b-badge>
              <b-badge variant="secondary">Git</b-badge>
              <b-badge variant="secondary">PHP</b-badge>
              <b-badge variant="secondary">Express JS</b-badge>
              <b-badge variant="secondary">C#</b-badge>
              <b-badge variant="secondary">.Net Básico</b-badge>
              <b-badge variant="secondary">Microsoft Visual Studio</b-badge>
              <b-badge variant="secondary">Unity Engine</b-badge>
              <b-badge variant="secondary">Paint.net</b-badge>
              <b-badge variant="secondary">Blender</b-badge>
              <b-badge variant="secondary">MongoDB</b-badge>
              <b-badge variant="secondary">Slim Framework</b-badge>
              <b-badge variant="secondary">Angular</b-badge>
              <b-badge variant="secondary">SQL</b-badge>
              <!-- /Otros Conocimiento -->
            </b-col>
            <!-- /Lado izquierdo -->
            <!-- Lado derecho -->
            <b-col md="8" class="mt-2 pl-4">
              <!-- Formación academica -->
              <b-card-title>Formación Académica</b-card-title>
              <b-list-group flush>
                <b-list-group-item>
                  <h6>Ingeniería en Sistemas y Redes Informáticas</h6>
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
                  <h6>Técnico Vocacional en Desarrollo de Software</h6>
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
              <!-- /Formación academica -->
              <!-- Proyectos -->
              <b-card-title>Proyectos Académicos y colaborativos</b-card-title>
              <b-list-group flush>
                <b-list-group-item>
                  <h6>Software de reporte ciudadano | <small>Académico</small></h6>
                  <div>
                    Angular, Firestore, Firebase Cloud Functions, Android
                    Vanilla
                  </div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Plataforma Bibliotech (buscador de contenido) | <small>Académico, Proyecto de horas sociales </small></h6>
                  <div>Angular, MongoDB, NodeJs Express</div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Software de administración de paqueteria</h6>
                  <div>ReactJs, MariaDB, NodeJs Express</div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Software de administración de iglesia | <small>Académico, Proyecto de pre-especialización de carrera</small></h6>
                  <div>ReactJs, MariaDB, NodeJs Express</div>
                </b-list-group-item>
              </b-list-group>
              <!-- /Proyectos -->
              <!-- Certificaciones -->
              <b-card-title>Certificaciones</b-card-title>
              <b-list-group flush>
                <b-list-group-item>
                  <h6>Cisco IT Essentials: PC Hardware and Software</h6>
                  <div>
                    Universidad Gerardo Barrios | Cisco Networking Academy
                  </div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Cisco CCNA R&S: Introduction to Networks</h6>
                  <div>
                    Universidad Gerardo Barrios | Cisco Networking Academy
                  </div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Cisco CCNA R&S: Routing and Switching Essentials</h6>
                  <div>
                    Universidad Gerardo Barrios | Cisco Networking Academy
                  </div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Cisco CCNA R&S: Connecting Networks</h6>
                  <div>
                    Universidad Gerardo Barrios | Cisco Networking Academy
                  </div>
                </b-list-group-item>
                <b-list-group-item>
                  <h6>Cisco CCNA R&S: Scaling Networks</h6>
                  <div>
                    Universidad Gerardo Barrios | Cisco Networking Academy
                  </div>
                </b-list-group-item>
              </b-list-group>
              <!-- /Certificaciones -->
              <!-- Otros cursos -->
              <b-card-title>Otros cursos</b-card-title>
              <b-list-group flush>
                <b-list-group-item>
                  <h6><a href="https://google.qwiklabs.com/course_templates/156" target="_blank">Google Cloud Computing Foundations: Data, ML, and AI in Google Cloud</a></h6>
                  <div>
                   <a href="https://google.qwiklabs.com/public_profiles/37a05d64-bec3-47d7-ab6d-68b27804341d" target="_blank">Badges de cursos finalizados</a>
                  </div>
                </b-list-group-item>
              </b-list-group>
                <!-- Otros cursos -->
            </b-col>
            <!-- /Lado derecho -->

          </b-row>
        </b-card>
      </b-col>
    </b-row>
  </fragment>
</template>

<script>
export default {
  name: 'index',
}
</script>
<style></style>
