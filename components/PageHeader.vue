<template>
  <header>
  <b-navbar class="nav px-2" toggleable="lg" type="dark" variant="primary">
    <b-navbar-brand href="/">
      <img src="https://placekitten.com/g/30/30" class="d-inline-block align-top" alt="Kitten">
      NUXT.IO
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="text-dark">
        <b-nav-item href="/blog/second-content" active>Second Content</b-nav-item>
        <b-nav-item href="/blog/third-content">Third Content</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <em>User</em>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</header>
</template>

<script>
export default {

}
</script>