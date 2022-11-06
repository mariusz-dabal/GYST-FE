<template>
  <v-app>
    <v-main>
      <Navbar />
      <v-container>
        <router-view></router-view>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </v-container>
      <Footer app />
    </v-main>
  </v-app>
</template>

<script setup>
  import Navbar from '@/components/Navbar.vue'
  import Footer from '@/components/Footer.vue'
</script>
