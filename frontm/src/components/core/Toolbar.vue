<template>
  <v-toolbar
    app
    color="blue"
    dark
    prominent
  >
    <v-toolbar-title class="headline">
      <span>Mais</span>
      <span class="font-weight-light"> Rep </span>
    </v-toolbar-title>
    

    <v-avatar
      color="grey"
      class="mr-3"
    />

    <v-btn
      v-for="n in 3"
      :key="n"
      flat
    >
      Item {{ n }}
    </v-btn>

    <v-spacer />

    <!--<v-flex xs4>
      <v-text-field
        solo-inverted
        flat
        hide-details
      />
    </v-flex>-->
  </v-toolbar>
</template>

<script>
  
  export default {
    components: {
    }      
  }
</script>

<style lang="scss" scoped>
  
</style>