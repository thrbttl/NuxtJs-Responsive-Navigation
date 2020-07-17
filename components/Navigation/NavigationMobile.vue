<template>
  <div id="navigation-mobile">
    <div class="navbar-collapse">
      <ul class="navbar-nav mr-auto">
        <router-link tag="li" to="/" class="items col-3">Home</router-link>
        <router-link tag="li" to="/Blogs" class="items col-3">Blogs</router-link>
        <router-link tag="li" to="/Projects" class="items col-3">Projects</router-link>
        <router-link tag="li" to="/Portfolio" class="items col-3">Portfolio</router-link>
        <router-link tag="li" to="/About" class="items col-3">About</router-link>
        <router-link tag="li" to="/Contact" class="items col-3">Contact</router-link>
      </ul>

      <div class="exitButton">
        <router-link tag="i" to class="fas fa-times"></router-link>
      </div>

      <div class="backButton">
        <router-link tag="i" to class="fas fa-sign-out-alt">
          <span>Back</span>
        </router-link>
      </div>

      <div class="social-media">
        <a href="https://twitter.com/tahirbattal" target="”_blank”">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="https://github.com/thrbttl" target="”_blank”">
          <i class="fab fa-github" aria-hidden="true"></i>
        </a>
        <a href="https://www.linkedin.com/in/tahir-battal-b6180318a/" target="”_blank”">
          <i class="fab fa-linkedin-in" aria-hidden="true"></i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {},
  computed: {}
};
</script>


<style scoped>
#navigation-mobile {
  padding: 80px 0 0 0;
  width: 100%;
}

ul {
  list-style: none;
  width: 100%;
  padding-left: 25px;
  padding-top: 20px;
}

.items {
  color: #fff !important;
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 20px;
  cursor: pointer;
}

@media only screen and (min-width: 768px) and (max-width: 1024px) {
  .items {
    font-size: 1.5rem;
  }
}
@media only screen and (min-width: 426px) and (max-width: 767px) {
  .items {
    font-size: 1rem;
  }
}
@media only screen and (min-width: 376px) and (max-width: 425px) {
  .items {
    font-size: 1rem;
  }
}
@media only screen and (min-width: 321px) and (max-width: 375px) {
  .items {
    font-size: 1rem;
  }
}
@media only screen and (max-width: 320px) {
  .items {
    font-size: 1rem;
  }
}

.items:hover {
  color: rgb(81, 122, 131) !important;
}

.social-media {
  position: absolute;
  left: 40px;
  top: 118%;
}

i {
  margin: 0 20px 0 0;
  color: #fff;
  font-size: 2rem;
  cursor: pointer;
}

i:hover {
  color: rgb(81, 122, 131) !important;
}

.exitButton {
  position: absolute;
  top: 30px;
  left: 40px;
}
.exitButton i {
  color: rgb(51, 96, 109);
}

.backButton {
  position: absolute;
  top: 100%;
  left: 40px;
}

.backButton i {
  font-size: 4rem;
  color: rgb(255, 255, 255);
}

@media only screen and (min-width: 426px) and (max-width: 767px) {
  .backButton i {
    font-size: 3rem;
  }
}
@media only screen and (min-width: 376px) and (max-width: 425px) {
  .backButton i {
    font-size: 2rem;
  }
}
@media only screen and (min-width: 321px) and (max-width: 375px) {
  .backButton i {
    font-size: 2rem;
  }
}
@media only screen and (max-width: 320px) {
  .backButton i {
    font-size: 2rem;
  }
}

.backButton span {
  font-size: 2rem;
  font-weight: bolder;
  position: absolute;
  top: 15px;
  left: 80px;
}

@media only screen and (min-width: 426px) and (max-width: 767px) {
  .backButton span {
    font-size: 2rem;
    top: 6px;
    left: 60px;
  }
}
@media only screen and (min-width: 376px) and (max-width: 425px) {
  .backButton span {
    font-size: 2rem;
    top: -1px;
    left: 50px;
  }
}
@media only screen and (min-width: 321px) and (max-width: 375px) {
  .backButton span {
    font-size: 2rem;
    top: -1px;
    left: 50px;
  }
}
@media only screen and (max-width: 320px) {
  .backButton span {
    font-size: 2rem;
    top: -2px;
    left: 50px;
  }
}
</style>
