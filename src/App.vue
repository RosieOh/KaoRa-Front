<template>
  <v-app>
    <v-container class="my-5">
      <v-row justify="center">
        <v-col cols="12" md="8" lg="6">
          <v-card class="pa-5" elevation="2">
            <v-card-title class="text-h5">
              Welcome to My Vuetify Page
            </v-card-title>
            <v-card-text>
              This is a simple page created using Vue 3 and Vuetify 3. Here, we have a card component with some text and a button.
            </v-card-text>
            <v-card-actions>
              <v-btn color="primary" @click="handleClick">Click Me</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
export default {
  methods: {
    handleClick() {
      alert("Button clicked!")
    },
  },
}
</script>

<style>
/* Vuetify가 이미 스타일을 제공하기 때문에 추가적인 스타일링은 필요하지 않습니다. */
</style>
