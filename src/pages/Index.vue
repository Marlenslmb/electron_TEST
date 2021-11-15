<template>
  <q-page class="flex flex-center">
    <q-page class="first">
      <router-link to="/first">
        <h2 class="hs">1</h2>
      </router-link>

    </q-page>
    <q-page class="second">
      <router-link to="/second">
        <h2 class="hs">2</h2>
      </router-link>

    </q-page>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';
import first from 'components/first';
import second from "components/second";
export default defineComponent({
  name: 'PageIndex',
  components: {
    first,
    second
  }
})
</script>
<style>
.flex{
  display: flex;
  justify-content: space-evenly;
}
.hs{
  text-decoration: none;
}
</style>
