<template>
  <h1>Mi primera app de Vue</h1>

  <h1>Hello world!</h1>

  <MenusNumerator :valorem="7" />

  <MenusNumeratorScript :valorem="10" />

  <MeusNumeratorScript2 :valorem="2" />
</template>

<script lang="ts" setup>
import MenusNumerator from './components/MenusNumerator.vue';
import MenusNumeratorScript from './components/MenusNumeratorScript.vue';
import MeusNumeratorScript2 from './components/meus-numerator-script/MenusNumeratorScript2.vue';
</script>
