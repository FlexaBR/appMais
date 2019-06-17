<template>
  <v-app>
    <core-toolbar />
    
    <core-view />
  </v-app>
</template>

<script>
import CoreToolbar from '@/components/core/Toolbar'
import CoreView from '@/components/core/View'
import { mapActions } from 'vuex'

export default {
  name: 'App',
  components: {
    CoreToolbar,
    CoreView
  },
  methods: mapActions(['setUsuario']),
	created() {
    this.setUsuario(null)
  }
}
</script>
