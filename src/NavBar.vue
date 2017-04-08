<template>
  <div class="nav-bar">
    <md-layout md-gutter>
      <md-layout md-flex="50"></md-layout>
      <md-layout></md-layout>
      <md-layout></md-layout>
      <md-layout></md-layout>
      <md-layout></md-layout>
      <md-layout>
        <md-button @click.native="toggleLeftSidenav">
          <md-icon>menu</md-icon>Contact
        </md-button>

        <md-sidenav class="md-left" ref="leftSidenav" @open="open('Left')" @close="close('Left')">
          <md-toolbar class="md-medium">
            <div class="md-toolbar-container">
              <h3 class="md-title">Contact Info.</h3>
            </div>
          </md-toolbar>
          <md-list class="md-double-line">
            <md-list-item>
              <md-icon class="md-primary">phone</md-icon>

              <div class="md-list-text-container">
                <span>097-039-4023</span>
                <span>Mobile</span>
              </div>
            </md-list-item>
            <md-list-item>
              <md-icon class="md-primary">email</md-icon>
              <div class="md-list-text-container">
                <span>nattakarn.kl@gmail.com</span>
                <span>Personal</span>
              </div>
            </md-list-item>
          </md-list>
        </md-sidenav>
      </md-layout>
    </md-layout>
  </div>
</template>

<script>
export default {
  methods: {
    toggleLeftSidenav () {
      this.$refs.leftSidenav.toggle()
    },
    open (ref) {
      console.log('Opened: ' + ref)
    },
    close (ref) {
      console.log('Closed: ' + ref)
    }
  }
}
</script>

<style lang="css">
  font-family: 'Open Sans', sans-serif;
  .btn-align {
    text-align: right;
  }
  .btn {
    color: #1A93E1;
  }
</style>
