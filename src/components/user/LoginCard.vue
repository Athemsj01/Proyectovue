<template>
  <v-card class="cardLogin">
    <v-card-title>LOGIN</v-card-title>
    <v-card-text>
      <v-form>
        <v-text-field 
        v-model="email"
        :rules="emailRules"
        label="E-mail"
        required
        />
        <v-text-field 
        v-model="password"
        label="Password"
        required
        />
      </v-form>
    </v-card-text>
    <v-card-actions>
      <v-btn> Cancel </v-btn>
      <v-btn> LogIn </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  setup () {

  },
}
</script>
<style>
.cardLogin {
  width: fit-content;
  min-width: 300px;
  height: fit-content;
}
</style>