<script setup lang="ts">
import LoginForm from "@/components/Login/LoginForm.vue";
import router from "@/router";


async function goHome() {
  void router.push({ name: "Home" });
}
</script>

<template>
  <main class="centered">
    <button @click="goHome" > BACK</button>

    <h1>Welcome Back</h1>
    <LoginForm />
    
  </main>
</template>

<style>

</style>
