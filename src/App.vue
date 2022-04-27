<template>
  <router-view />
</template>

<script lang="ts">
import { defineComponent } from 'vue';

import '@unocss/reset/tailwind.css';
import 'uno.css';

export default defineComponent({
  name: 'App',
});
</script>
