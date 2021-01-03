<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-button variant="dark" v-b-toggle.sidebar-backdrop><i class="fas fa-bars"></i></b-button>
      </b-navbar-nav>

      <b-navbar-nav class="ml-auto">
        <b-nav-item class="mr-3">
          <i class="fas fa-bell"></i>
        </b-nav-item>

        <b-nav-item class="mr-3">
          <i class="fas fa-user"></i>
        </b-nav-item>

        <b-nav-item>
          <i class="fas fa-power-off"></i>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style scoped>
</style>
