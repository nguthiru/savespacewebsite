<template >
  <div>
    <div class="nav-container">
      <div class="navbar">
        <router-link to="/">
          <img id="logo" src="../assets/logo.png" alt="savespace logo" />
        </router-link>
        <div class="nav-links">
          <ul>
            <router-link to="/features"> <li>Features</li></router-link>
            <router-link to="/support"> <li>Support</li></router-link>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "navbar",
};
</script>
