<script>
export default {
  name: "Header",};
</script>

<template>
  <header class="bg-gray-900 text-white p-4 flex justify-between items-center shadow-md">
    <!-- Left Side -->
    <div class="text-lg font-semibold">
      <a href="#internships" class="hover:underline">Internships</a>
    </div>

    <!-- Right Side -->
    <nav class="space-x-6 text-sm">
      <a href="/resume.pdf" target="_blank" class="hover:underline">Resume/CV</a>
      <a href="#about" class="hover:underline">About</a>
      <a href="#projects" class="hover:underline">Projects</a>
    </nav>
  </header>
</template>

<style scoped>

</style>