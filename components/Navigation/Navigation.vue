<template>
  <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="navigation">
    <router-link tag="a" to="/" class="navbar-brand ml-3 mr-5">
      <img src="../../static/image/logo.png" width="30" alt="tahir battal" />
    </router-link>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav mr-auto">
        <router-link tag="li" to="/" class="items">Home</router-link>
        <router-link tag="li" to="/Blogs" class="items">Blogs</router-link>
        <router-link tag="li" to="/Projects" class="items">Projects</router-link>
        <router-link tag="li" to="/Portfolio" class="items">Portfolio</router-link>
        <router-link tag="li" to="/About" class="items">About</router-link>
        <router-link tag="li" to="/Contact" class="items">Contact</router-link>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      show: null
    };
  },
  methods: {
  },
  computed: {
  }
};
</script>

<style scoped>
#navigation {
  display: flex;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
  margin-bottom: 40px;
  border: 1px solid transparent;
  border-radius: 0px;
}
.navbar {
  background-color: #1a1a1a !important;
}

ul {
  display: flex;
  list-style: none;
  padding: 0;
  margin: 0 20px 0 0;
}
.items {
  font-size: 22px;
  padding: 2px 10px;
  cursor: pointer;
  color: rgb(255, 255, 255);
}
.items:hover {
  color: rgb(88, 140, 88);
}

.fixed-top {
  position: fixed !important;
  top: 0px !important;
}
</style>