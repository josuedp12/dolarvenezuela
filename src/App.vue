<template>
  <div class="app">
    <div class="dashboard-main-wrapper">
      <navbar />
      <sidebar />
    </div>
  </div>
</template>

<script>
import navbar from "@/components/navbar";
import sidebar from "@/components/sidebar";

export default {
  name: "App",
  components: { navbar, sidebar }
};
</script>

<style></style>
