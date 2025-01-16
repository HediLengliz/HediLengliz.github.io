<template>
  <div>
    <Header />
    <!-- Render the current page -->
    <main class="p-8">
      <NuxtPage />
    </main>
  </div>

</template>
<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header,
  },
};
</script>