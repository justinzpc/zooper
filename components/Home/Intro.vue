<template>
  <div class="space-y-6">
    <NuxtImg src="/Head_Portraits.jpeg" alt="Fayaz Ahmed"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm JustinZhao, I work as a frontEnd software from
      FoShan, China. I specialize in building web applications and sites
      using Javascript, React, Vue &amp; Node. I've carved out my own little
      nook on the internet to share my life and some interesting things i was experienced
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Fayaz Ahmed",
  description:
    "I'm Fayaz, your friendly neighborhood software, product engineer and designer from Bengaluru, India. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>
