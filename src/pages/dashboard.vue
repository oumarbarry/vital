<script setup>
useTitle('Vital - Admin');
</script>

<template>
  <q-page
    class="flex flex-col flex-center space-y-30 bg-[#18161e] text-gray-50"
  >
    <div uppercase>Welcome to the Dashboard Page</div>
    <Footer />
  </q-page>
</template>

<route lang="yaml">
meta:
  layout: admin
</route>
