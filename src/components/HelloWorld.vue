<template>
  <v-container>
    <v-card>
      <v-card-title>{{user.name}}</v-card-title>
      <v-card-subtitle>{{user.lastname}}</v-card-subtitle>
    </v-card>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    user: {
      name: 'John',
      lastname: 'Doe'
    }
  })
}
</script>
