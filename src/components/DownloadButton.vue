<template>
  <div class="flex items-center cursor-pointer">
    <p
      class="bg-[var(--button-download)] text-white px-[1rem] py-[0.5rem] rounded-[var(--radius)] transition hover:bg-[var(--button-download-hover)]"
      @click="downloadApp"
    >
      СКАЧАТЬ
    </p>
  </div>
</template>

<script setup>
import { downloadApp } from "../lib/utils";
</script>
