<template>
  <header class="header">
    <div class="container">
      <HeaderInner />
    </div>
  </header>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import HeaderInner from 'HeaderInner.vue';

  export default defineComponent({
    name: 'Header',
    components: {
      HeaderInner
    }
  })
</script>

<style scoped>

/* Header */

.header__inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 12rem;
}
.header__btn {
  border: none;
  background: transparent;
  cursor: pointer;
}

.logo {
  margin: 0 auto;
}

.menu {
  padding-right: 1.5rem;
  font-size: 1.6rem;
}
.menu__list {
  display: flex;
}
.menu__list-item {
  padding-right: 4.5rem;
  padding-left: 3.5rem;
}
.menu__list-link {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  color: rgba(54, 56, 56, 0.9);
}
</style>

