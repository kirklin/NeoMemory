<template>
  <div
    class="sticky top-0 z-30 flex h-16 w-full justify-center bg-opacity-90 text-base-content backdrop-blur transition-all duration-100"
  >
    <nav class="navbar w-full">
      <div class="flex flex-1 md:gap-1 lg:gap-2">
        <router-link
          to="/"
          aria-current="page"
          aria-label="Homepage"
          class="flex-0 btn btn-ghost px-2"
        >
          <div
            class="font-title inline-flex text-lg text-primary transition-all duration-200 md:text-3xl"
          >
            <span class="text-accent">N<span class="lowercase">eo</span></span>
            <span class="text-base-content">M<span class="lowercase">emory</span></span>
          </div>
        </router-link>
      </div>
      <div class="flex-0">
        <ThemeChange />
      </div>
    </nav>
  </div>
</template>
<script setup lang="ts">
import ThemeChange from "./components/ThemeChange.vue";
</script>
