<template>
  <main class="min-h-screen">
    <AppHeader class="mb-12" title="Projects" :description="description" />
    <div class="space-y-4">
      <AppProjectCard
        v-for="(project, id) in projects"
        :key="id"
        :project="project"
      />
    </div>
  </main>
</template>

<script setup>
const description =
  "I’ve worked on tons of projects over the years but these are the ones that I’m most proud of. Many of them are private project for my clients. More details  & images about these project soon.";
useSeoMeta({
  title: "Projects | Fayaz Ahmed",
  description,
});

const { data: projects } = await useAsyncData("projects-all", () =>
  queryContent("/projects").find()
);
</script>
