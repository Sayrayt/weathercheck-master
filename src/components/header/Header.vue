<template>
  <v-app-bar :color="this.$vuetify.breakpoint.mdAndUp ? 'accent' : 'transparent'"
             absolute
             app
             class="header"
             dark
             flat
  >
    <v-row class="align-center">
      <v-col class="header__nav d-flex align-center" cols="12">
        <div class="header__logo">
          <img :src="require('@/assets/icon/logo.png')" alt="logo">
        </div>
      </v-col>
    </v-row>
  </v-app-bar>
</template>

<script>

export default {
  name: "Header"
}
</script>

<style scoped>
</style>