<template>
  <h1>Mi primera app de Vue</h1>
  <MenusNumerator :valorem="7" />

  <MenusNumeratorScript :valorem="10" />
</template>

<script lang="ts" setup>
import MenusNumerator from './components/MenusNumerator.vue';
import MenusNumeratorScript from './components/MenusNumeratorScript.vue';
</script>
