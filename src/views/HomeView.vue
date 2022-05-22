<template>
  <v-sheet height="100vh" width="100vw" class="background">
    <v-row no-gutters justify="center" align="center" style="height: 100vh" >
       <login-card-vue />
    </v-row>
   
  </v-sheet>
</template>

<script>
import { defineComponent } from "vue";

//Components
import LoginCardVue from "@/components/user/LoginCard.vue";

export default defineComponent({
  name: "HomeView",
  components : {
    LoginCardVue
},
});
</script>
<style>
.background {
  background-color: bisque;
}
</style>