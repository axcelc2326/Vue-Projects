<template>
  <div>
    <h1 v-if="user.isLoggedIn">Welcome back, {{ user.name }}! The battlefield is waiting for you!</h1>
    <h1 v-else>Please log in.</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        isLoggedIn: true,
        name: 'Axcel'
      }
    };
  }
};
</script>
