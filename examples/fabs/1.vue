<template>
  <v-fab primary light  @click.native="change" ref="fab" lateral>
    <v-icon light>{{ icon ? 'add' : 'list' }}</v-icon>
  </v-fab>
</template>

<script>
  export default {
    data: () => ({
      icon: false
    }),
    methods: {
      change () {
        this.$refs.fab.changeAction()
        this.icon = !this.icon
      }
    }
  }
</script>