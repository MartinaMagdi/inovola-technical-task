<template>
  <div class="footer">
    <div>
      <img src="../../assets/images/zid-logo-2.png" alt="logo" />
      <ul class="social-container">
        <li class="social-item">
          <a>
            <v-icon>mdi-twitter</v-icon>
          </a>
        </li>
        <li class="social-item">
          <a>
            <v-icon>mdi-instagram</v-icon>
          </a>
        </li>
        <li class="social-item">
          <a>
            <i class="fab fa-linkedin-in"></i>
          </a>
        </li>
        <li class="social-item">
          <a>
            <v-icon>mdi-youtube</v-icon>
          </a>
        </li>
      </ul>
    </div>
    <div class="buttons-container">
      <button>
        <v-icon class="message-icon">mdi-forum</v-icon>
      </button>
      <button @click="scrollToTop()">
        <v-icon class="arrow-icon">mdi-arrow-up</v-icon>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",

  data: () => ({}),

  methods: {
    scrollToTop() {
      window.scrollTo(0, 0);
    },
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/styles/variables";
@import "../../assets/styles/Layouts/Footer";
</style>
