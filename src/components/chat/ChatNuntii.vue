<template>
  <div class="p-4 flex-1 overflow-y-auto">
    <div class="flex flex-col space-y-2">
      <ChatBullula v-for="nuntius in nuntii" :key="nuntius.id" v-bind="nuntius" />
    </div>
  </div>
</template>

<script lang="ts" setup>
import type { ChatNuntius } from '@/interfaces/chat-nuntius.interface';
import ChatBullula from './ChatBullula.vue';

interface Props {
  nuntii: ChatNuntius[];
}

defineProps<Props>();
</script>
