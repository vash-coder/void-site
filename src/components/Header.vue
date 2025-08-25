<template>
  <div
    class="flex justify-between p-7"
    style="background-color: var(--background)"
  >
    <p class="text-[var(--void-text)] font-[700] text-[1.5rem]">VOID</p>
    <DownloadButton />
  </div>
</template>

<script setup>
import DownloadButton from "./DownloadButton.vue";
</script>
