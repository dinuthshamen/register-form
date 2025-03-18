<script setup>
import CreateAccount from './pages/register.vue'
</script>

<template >
  <div class="account-container">
    <CreateAccount />
  </div>
</template>


<style scoped>
.account-container {
  margin-top: 20px;
  padding: 16px; /* Adds padding for better spacing */
  max-width: 500px; /* Restricts form width */
  width: 100%;
  margin-left: auto;
  margin-right: auto;
}

/* Mobile responsiveness */
@media (max-width: 768px) {
  .account-container {
    padding: 10px; /* Reduce padding on smaller screens */
    max-width: 90%; /* Allow form to use more screen space */
  }
}
</style>