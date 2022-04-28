<script setup>
const tab = $ref('home');
</script>

<template>
  <div class="flex flex-col flex-center">
    <q-tabs v-model="tab" active-class="text-teal">
      <q-route-tab
        name="home"
        class="i-carbon-session-border-control self-center m-5 w-7"
        to="/"
      />
      <q-route-tab
        name="dashboard"
        class="i-carbon-fingerprint-recognition self-center m-5 w-7"
        to="/dashboard"
      />
      <q-route-tab
        class="i-carbon-logo-github self-center m-5 w-7"
        href="https://github.com/oumarbarry/vital"
        target="_blank"
      />
    </q-tabs>

    <div text-center text-yellow-300>*Auto-Imported Footer*</div>
  </div>
</template>
