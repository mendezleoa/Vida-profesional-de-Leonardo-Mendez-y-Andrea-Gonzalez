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
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Personalidad'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="academic" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Información academica'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="experience" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Experiencia laboral'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="skills" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Habilidades'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="contacto" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Contacto'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="ubication" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Ubicación'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-col>
    <v-col cols="12" md="2" order="1" order-md="0" class="text-center">
      <div class="text-body-1 font-weight-light mb-2">Desarrollado con</div>
      <div class="d-sm-flex d-md-block align-center justify-center">
        <v-sheet class="flex-grow-1">
          <v-img height="100" src="@/assets/logo.svg" />
          <p class="text-body-1 font-weight-bold">Vuetify</p>
        </v-sheet>
        <v-sheet class="flex-grow-1">
          <v-img height="100" src="@/assets/logo.svg" />
          <p class="text-body-1 font-weight-bold">Vue</p>
        </v-sheet>
        <v-sheet class="flex-grow-1">
          <v-img height="100" src="@/assets/logo.svg" />
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
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Personalidad'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="academic" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Información academica'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="experience" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Experiencia laboral'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="skills" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Habilidades'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="contacto" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Contacto'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
        <v-expansion-panel key="ubication" hide-actions>
          <v-expansion-panel-title>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
              <v-col
                cols="4"
                sm="2"
                md="1"
              >

              </v-col>

              <v-col
                class="hidden-xs-only text-left ms-2"
              >
                <strong v-html="'Ubicación'"></strong>
              </v-col>
            </v-row>
          </v-expansion-panel-title>
          <v-expansion-panel-text>
            <v-card-text v-text="'lorem'"></v-card-text>
          </v-expansion-panel-text>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-col>
  </v-container>
</template>

<script setup>
  //
</script>
