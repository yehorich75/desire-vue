<template>

  <Header>
    <HeaderInner />
  </Header>

</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Header from './components/Header.vue'
import HeaderInner from './components/HeaderInner.vue'

export default defineComponent({
  name: 'App',
  components: {
    Header,
    HeaderInner
  }
})
</script>
