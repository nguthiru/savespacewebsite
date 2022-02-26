<template>
  <navbar />
  <main>
    <router-view/>
  </main>
</template>

<script>
import navbar from "../src/components/navbar.vue";
export default {
  name: "App",
  components: {
    navbar,
  },
};
</script>

