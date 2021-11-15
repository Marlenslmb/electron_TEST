<template>
  <router-link to="/">
    <q-page class="first">
      <h2>BACK TO MAIN</h2>
    </q-page>
  </router-link>
</template>

<script>

export default {
  name: "first",
  data(){
    return{
      title: 'FIRST 1'
    }
  }
}
</script>

<style scoped>
.first {
  display: flex;
  justify-content: center;
}
</style>
