<template>
  <div class="dashboard">
    <h1>Dashboard</h1>
    <p>Welcome to your dashboard!</p>
  </div>
</template>

<script>
export default {
  name: "Dashboard",
  data() {
    return {
      message: "This is your dashboard component."
    };
  }
};
</script>

<style scoped>
.dashboard {
  padding: 20px;
  background-color: #f9f9f9;
}
h1 {
  color: #333;
}
</style>
