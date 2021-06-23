<template>
  <header class="header">
    <div class="container">
      <HeaderInner />
    </div>
  </header>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import HeaderInner from './HeaderInner.vue';

  export default defineComponent({
    name: 'Header',
    components: {
      HeaderInner
    }
  })
</script>

