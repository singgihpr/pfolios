<template>
  <div class="space-y-6">
    <NuxtImg src="/singgih.jpg" alt="Singgih Aji"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      My name is Singgih Aji, I'm a Fullstack Web Developer from
      Jakarta, Indonesia.<br /> I specialize in building web applications and sites
      using Laravel, Vue &amp; Nuxt. Also, I'm a father to a daughter and husband to beautiful wife.
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a Fullstack Web Developer doubles as Project Manager at
      <a href="https://salamsolusi.com" target="_blank" class="underline">salamsolusi</a>, and
      by night (and weekends), I'm busy side hustling for my family.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Singgih Aji",
  description:
    "I'm Singgih, I work as a Fullstack Web Developer from Jakarta, Indonesia. I specialize in building web applications and sites using Laravel, Vue & Nuxt.",
});
</script>
