<template>
  <header>
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/login">로그인</router-link>
    </div>
    <hr />
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  },
});
</script>

<style></style>
