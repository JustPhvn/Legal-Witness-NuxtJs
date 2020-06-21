<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-container>
        <b-navbar-brand to="/">Legal Expert Witness</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav> </b-navbar-nav>

          <b-navbar-nav class="ml-auto">
            <b-nav-item to="/about">About</b-nav-item>
            <b-nav-item-dropdown text="Witnesses" right>
              <b-dropdown-item to="/wone">W. One</b-dropdown-item>
              <b-dropdown-item>W. Two</b-dropdown-item>
              <b-dropdown-item>W. Three</b-dropdown-item>
              <b-dropdown-item>W. Four</b-dropdown-item>
            </b-nav-item-dropdown>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style>
.navbar {
  background-color: #0f0f0f !important;
}
</style>
