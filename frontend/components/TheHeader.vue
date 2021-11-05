<template>
  <div>
    <v-app-bar dark color="#444">
      <v-toolbar-title
        @click="$router.push('/')"
        class="headline text-uppercase"
        style="cursor: pointer"
      >
        Workout Tracker
      </v-toolbar-title>

      <v-spacer></v-spacer>
      <v-btn text>Bye</v-btn>
      <v-btn text>Hello</v-btn>
      <v-btn text>Hello</v-btn>
      <v-btn text>Hello</v-btn>
    </v-app-bar>
  </div>
</template>