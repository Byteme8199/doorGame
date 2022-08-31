<template>
  <div class="nav-container">
    <nav class="navbar navbar-expand-md navbar-light bg-light">
      <div class="container">
        <div class="navbar-brand logo"></div>
        <MainNav />
        <AuthNav />
      </div>
    </nav>
  </div>
</template>

<script>
import MainNav from "@/components/MainNav";
import AuthNav from "@/components/AuthNav";

export default {
  name: "NavBar",
  components: { AuthNav, MainNav },
};
</script>
