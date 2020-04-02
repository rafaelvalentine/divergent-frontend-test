<template>
  <div class="_navbar">
    <b-navbar toggleable="lg" type="dark" variant="transparent" class='navbar-toolbelt'>
      <b-navbar-brand href="#">
        <img :src="logo" alt="Kitten" />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-navbar-nav class="links">
            <b-nav-item href="#" class="link-routes">How it works</b-nav-item>
            <b-nav-item href="#" class="link-routes">Perks</b-nav-item>
          </b-navbar-nav>
          <b-nav-form>
            <b-link to="/">
              <b-button size="md" class="my-2 my-sm-0" type=""
                >Register</b-button
              >
            </b-link>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
import logo from "../sass/avatars/logo.svg";
export default {
  name: "",
  props: {
    msg: String
  },
  data: function() {
    return {
      logo: logo
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="../sass/components/Navbar.sass" scoped lang="sass"></style>
