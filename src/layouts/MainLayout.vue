<template>
  <q-layout view="lHr Lpr lFr">
    Hello
    <q-header>
      <q-toolbar>
        <q-avatar>
          <img src="" alt="logo" />
        </q-avatar>

        <q-toolbar-title class="row justify-center">
          Yatzkan Woodworks
        </q-toolbar-title>

        <q-btn flat no-caps label="Shop" />
        <q-btn flat no-caps label="About" />
        <q-btn flat no-caps label="Contact" />
      </q-toolbar>
    </q-header>
    <q-page-container class="page-container" style="padding: 0">
      <router-view />
    </q-page-container>
    <q-footer>footer</q-footer>
  </q-layout>
</template>
<script setup lang="ts"></script>

<style scoped></style>
