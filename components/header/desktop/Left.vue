<script setup lang="ts">

import {BellIcon, BookmarkIcon, MagnifyingGlassIcon, UserCircleIcon} from "@heroicons/vue/24/outline";
</script>

<template>
  <div class="flex items-center space-x-2">
    <button class="w-[48px] h-[48px] bg-[#1B1C1F] rounded-[4px] p-[12px] flex justify-center items-center">
      <UserCircleIcon class="size-6 text-white" />
    </button>
    <button class="w-[48px] h-[48px] bg-[#1B1C1F] rounded-[4px] p-[12px] flex justify-center items-center">
      <MagnifyingGlassIcon class="size-6 text-white" />
    </button>
    <button class="w-[48px] h-[48px] bg-[#1B1C1F] rounded-[4px] p-[12px] flex justify-center items-center">
      <BookmarkIcon class="size-6 text-white" />
    </button>
    <button class="w-[48px] h-[48px] bg-[#1B1C1F] rounded-[4px] p-[12px] flex justify-center items-center">
      <BellIcon class="size-6 text-white" />
    </button>
  </div>

</template>

<style scoped>

</style>