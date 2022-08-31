<template>
  <Loading v-if="$auth.isLoading" />
  <div v-else id="app" class="d-flex flex-column h-100">
    <template>
      <NavBar />
      <router-view />
    </template>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";
import Loading from "@/components/Loading";

export default {
  components: {
    Loading,
    NavBar,
  },
};
</script>
