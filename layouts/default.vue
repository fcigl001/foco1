<template>
  <v-app :theme="theme">
    <v-app-bar elevation="2"
      absolute
    >
    <v-img style="margin-left: 40px"
        lazy-src="/image/logo.png"
        max-height="150"
        max-width="250"
        src="/image/logo.png"
></v-img>
  <v-spacer></v-spacer>
      <v-btn nuxt to="/">Home</v-btn>
      <v-btn nuxt to="/about">About</v-btn>
      <v-btn nuxt to="/pricing">Pricing</v-btn>
      <v-btn nuxt to="/contactus">Contact Us</v-btn>

      <v-btn
        :prepend-icon="theme === 'light' ? 'mdi-weather-sunny' : 'mdi-weather-night'"
        @click="onClick"
      >Toggle Theme</v-btn>
    </v-app-bar>

    <v-main>
       <slot />
    </v-main>
    <v-footer :absolute="fixed" app style="background: linear-gradient(to left, #8e9eab,#eef2f3 ">
        <span>&copy; Forrester Cohen International Group Limited {{ new Date().getFullYear() }}.</span>
      </v-footer>

  </v-app>
</template>

<script setup>
  import { ref } from 'vue'

  const theme = ref('light')

  function onClick () {
    theme.value = theme.value === 'light' ? 'dark' : 'light'
  }
</script>