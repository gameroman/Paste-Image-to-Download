<script lang="ts" setup>
import { toggleDark } from '~/composables'
</script>

<template>
  <nav class="mt-6 text-center text-xl">
    <RouterLink title="Home" class="icon-btn mx-2" to="/">
      <div class="i-carbon-campsite" />
    </RouterLink>

    <RouterLink title="About" class="icon-btn mx-2" to="/about">
      <div class="i-carbon-dicom-overlay" />
    </RouterLink>

    <div class="mt-2">
      <button title="Toggle dark mode" class="icon-btn mx-2" type="button" @click="toggleDark()">
        <div class="i-carbon-sun dark:i-carbon-moon" />
      </button>

      <a
        class="icon-btn mx-2" href="https://github.com/AlejandroAkbal/Paste-Image-to-Download" rel="noreferrer" target="_blank" title="GitHub"
      >
        <div class="i-carbon-logo-github" />
      </a>
    </div>
  </nav>
</template>
