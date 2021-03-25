<template>
  <v-container
    id="user-profile-view"
    fluid
    tag="section"
  >
    <v-row justify="center">
      <v-col
        cols="12"
        md="8"
      >
        <material-card
          color="primary"
          icon="mdi-account-outline"
        >
          <template #title>
            Editar perfil — <small class="text-body-1">Completar perfil</small>
          </template>

          <v-form>
            <v-container class="py-0">
              <v-row>
                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    disabled
                    label="Territorio"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    color="purple"
                    label="Nombre"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    color="purple"
                    label="Email"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="6"
                >
                  <v-text-field
                    color="purple"
                    label="Apellido Paterno"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="6"
                >
                  <v-text-field
                    color="purple"
                    label="Apellido Materno"
                  />
                </v-col>

                <v-col cols="12">
                  <v-text-field
                    color="purple"
                    label="Calle"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    color="purple"
                    label="Colonia"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    color="purple"
                    label="Estado"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    color="purple"
                    label="Codigo"
                    type="number"
                  />
                </v-col>

                <v-col
                  cols="12"
                  class="text-right"
                >
                  <v-btn
                    color="primary"
                    min-width="150"
                    disabled
                  >
                    Actualizar perfil
                  </v-btn>
                </v-col>
              </v-row>
            </v-container>
          </v-form>
        </material-card>
      </v-col>

      <v-col
        cols="12"
        md="4"
      >
        <app-card class="mt-4 text-center">
          <v-img
            class="rounded-circle elevation-6 mt-n12 d-inline-block"
            src="../assets/srcPerfil/default_perfil.png"
            width="128"
          />

          <v-card-text class="text-center">
            <h6 class="text-h6 mb-2 text--secondary">
              Tecnico
            </h6>

            <h4 class="text-h4 mb-3 text--primary">
              Nombre del Técnico
            </h4>

            <p class="text--secondary">
              Más información del tecnico
            </p>

            <v-btn
              class="mr-0"
              color="primary"
              min-width="100"
              rounded
            >
              Información
            </v-btn>
          </v-card-text>
        </app-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default { name: 'Perfil de Usuario' }
</script>
