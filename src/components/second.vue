<template>
  <router-link to="/">
    <q-page class="second">
      <h2>BACK TO MAIN</h2>
    </q-page>
  </router-link>
</template>

<script>
export default {
  name: "second",
  data() {
    return {
      title: 'SECOND 2'
    }
  }
}
</script>

<style scoped>
.second{
  display: flex;
  justify-content: center;
}
</style>
