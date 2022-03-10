<template>
  <div>
    <b-navbar toggleable="lg" type="dark">
      <div class="container mt-4">
        <img src="../assets/images/Geekgarden-logo.png" width="100px" />

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <li class="nav-item">
              <router-link
                class="nav-link text-light pl-3 pr-3"
                to="/keranjang"
              >
                Technical Test Muhammad Dzaki Era Davala
              </router-link>
            </li>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>


<script>
export default {
  name: "Hero",
};
</script>