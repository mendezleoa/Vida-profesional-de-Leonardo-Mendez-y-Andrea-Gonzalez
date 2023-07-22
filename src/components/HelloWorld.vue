<template>
  <v-container class="fill-height mx-auto">
    <v-col cols="12" md="5">
      <v-sheet class="mx-auto d-flex flex-column align-center" width="fit-content">
        <v-avatar size="80px">
          <v-img
            alt="Avatar"
            src="https://avatars.githubusercontent.com/u/92312161?s=48&v=4"
          ></v-img>
        </v-avatar>
        <strong v-html="'Leonardo Mendez'" class="my-3"></strong>
      </v-sheet>
      <v-expansion-panels variant="popout" class="pa-4">
        <v-expansion-panel key="personality" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-face-man-shimmer"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Personalidad'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'Grandes aspiraciones personales con un sentido del trabajo en equipo e interés en aprender y mejorar. Siempre en busca de nuevos desafíos para enfrentarlos con conocimiento y dedicación.'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="academic" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-account-school"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Información académica'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              Técnico medio en Informática
              <br />
              ETC Madre Rafols, Valera | 2014 – 2020
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="experience" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-badge-account-outline"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Experiencia laboral'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              CANTV | Técnico Suplente
              <br />
              Analista de Datos e información.
              <br />
              Servicio técnico de maquinaria.
              <br />
              Valera | Abril 2020 – Junio 2020
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="skills" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-account-star"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Habilidades'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              • Uso de tecnologías como computadoras de escritorio, impresoras, cámaras digitales y demás equipos electrónicos.
              <br />
              • Conocimiento programático en lenguajes como C#, Python o JavaScript.
              <br />
              • Uso de lenguaje inglés avanzado.
              <br />
              • Facilidad para entrar en un grupo de trabajo.
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="contacto" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-card-account-phone"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Contacto'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              Email: leonardoamm1100@gmail.com
              <br />
              Tlf.: 0412-5803255
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="ubication" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
              <v-icon icon="mdi-map-marker-account"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Ubicación'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'Urbanización Brisas del Araguaney, El Turagual. Carvajal, edo. Trujillo.'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-col>
    <v-col cols="12" md="2" order="1" order-md="0" class="text-center">
      <div class="text-body-1 font-weight-light mb-2">Desarrollado con</div>
      <div class="d-sm-flex d-md-block align-center justify-center">
        <v-sheet class="flex-grow-1 py-3">
          <v-img height="100" src="https://cdn.vuetifyjs.com/docs/images/logos/vuetify-logo-v3-slim-text-light.svg" />
        </v-sheet>
        <v-sheet class="flex-grow-1 py-3">
          <v-img height="100" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png" />
          <p class="text-body-1 font-weight-bold">Vue.js</p>
        </v-sheet>
        <v-sheet class="flex-grow-1 py-3">
          <v-img height="100" src="https://vitejs.dev/logo.svg" />
          <p class="text-body-1 font-weight-bold">Vite</p>
        </v-sheet>
      </div>
    </v-col>
    <v-col cols="12" md="5">
      <v-sheet class="mx-auto d-flex flex-column align-center" width="fit-content">
        <v-avatar size="80px">
          <v-img
            alt="Avatar"
            src="https://avatars.githubusercontent.com/u/89424193?s=64&v=4"
          ></v-img>
        </v-avatar>
        <strong v-html="'Andrea Gonzalez'" class="my-3"></strong>
      </v-sheet>
      <v-expansion-panels variant="popout" class="pa-4">
        <v-expansion-panel key="personality" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-face-woman-shimmer"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Personalidad'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              Soy una persona altamente motivada y orientada a resultados con una fuerte ética de trabajo. Me gusta el trabajo en equipo y tengo excelentes habilidades interpersonales y de comunicación.
              <br />
              Tengo un historial comprobado de éxito en mis funciones anteriores. Me considero de aprendizaje rápido y manejo varios programas de software.
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="academic" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-account-school"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Información académica'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              Técnico medio en Informática
              <br />
              ETC Madre Rafols, Valera | 2014 – 2020
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="experience" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-badge-account-outline"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Experiencia laboral'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              Desarrolladora Front End en CAISerT (compañía anónima al servicio tecnosocial)
              <br />
              Valera | 2021 – Actualidad
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="skills" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
              <v-icon icon="mdi-account-star"></v-icon>
            </v-col>
            <v-col class="hidden-xs-only text-left ms-2">
              <strong v-html="'Habilidades'"></strong>
            </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              • Manejo de software de diseño para UI/UX.
              <br />
              • Conocimiento programático en lenguajes de desarrollo web como Python, JavaScript, CSS, entre otros.
              <br />
              • Conocimiento programático en Frameworks de Javascript como Vue y React.
                <br />
                Ademas de manejo de preprocesadores de CSS como SASS
              <br />
              • Uso de lenguaje inglés avanzado.
              <br />
              • Facilidad para entrar en un grupo de trabajo.
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="contacto" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-card-account-phone"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Contacto'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text>
              Email: aderabg1@gmail.com
              <br />
              Tlf.: 0424-7528433
              <br />
              telegram: @Aderawa
            </v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="ubication" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col cols="2">
                <v-icon icon="mdi-map-marker-account"></v-icon>
              </v-col>
              <v-col class="hidden-xs-only text-left ms-2">
                <strong v-html="'Ubicación'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'Av. Santa barbara, Sector las pulgas. Valera, edo. Trujillo.'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-col>
  </v-container>
</template>
