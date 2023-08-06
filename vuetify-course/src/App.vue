<template>
  <v-app>
    <v-app-bar flat class="border-b">
      <v-app-bar-title> Título Componentizado</v-app-bar-title>
    </v-app-bar>
    <v-main>
      <v-container>
        <h1>Dashboard</h1>
        <v-row>
          <v-col cols="12" md="4" lg="3">
            <v-card flat class="border">
              <v-img
                src="https://images.pexels.com/photos/14059766/pexels-photo-14059766.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
                class="align-end text-white"
              >
                <v-card-title> Top 10 Praias da Bahia</v-card-title>
              </v-img>

              <v-card-subtitle class="pt-3"
                >Conheça o melhor do Nordeste</v-card-subtitle
              >
              <v-card-text>
                <div>Rio Vermelho</div>
                <div>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Eveniet odit unde commodi illo tempore quibusdam aut amet
                  optio mollitia animi.
                </div>
              </v-card-text>
              <v-card-actions>
                <v-btn color="primary" variant="outlined">Ver mais</v-btn>
                <!-- <v-btn color="warning" variant="tonal">Comprar</v-btn> -->
                <v-btn
                  prepend-icon=" mdi-cart"
                  color="success"
                  variant="outlined"
                  >Comprar</v-btn
                >
              </v-card-actions>
            </v-card></v-col
          >
          <v-col cols="12" md="4" lg="3">
            <v-card flat class="border">
              <v-img
                src="https://images.pexels.com/photos/14059766/pexels-photo-14059766.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
                class="align-end text-white"
              >
                <v-card-title> Top 10 Praias da Bahia</v-card-title>
              </v-img>

              <v-card-subtitle class="pt-3"
                >Conheça o melhor do Nordeste</v-card-subtitle
              >
              <v-card-text>
                <div>Rio Vermelho</div>
                <div>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Eveniet odit unde commodi illo tempore quibusdam aut amet
                  optio mollitia animi.
                </div>
              </v-card-text>
              <v-card-actions>
                <v-btn>Ver mais</v-btn>
              </v-card-actions>
            </v-card></v-col
          >
          <v-col cols="12" md="4" lg="3">
            <v-card flat class="border">
              <v-img
                src="https://images.pexels.com/photos/14059766/pexels-photo-14059766.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
                class="align-end text-white"
              >
                <v-card-title> Top 10 Praias da Bahia</v-card-title>
              </v-img>

              <v-card-subtitle class="pt-3"
                >Conheça o melhor do Nordeste</v-card-subtitle
              >
              <v-card-text>
                <div>Rio Vermelho</div>
                <div>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Eveniet odit unde commodi illo tempore quibusdam aut amet
                  optio mollitia animi.
                </div>
              </v-card-text>
              <v-card-actions>
                <v-btn>Ver mais</v-btn>
              </v-card-actions>
            </v-card></v-col
          >
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
