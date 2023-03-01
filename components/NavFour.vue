<template>
  <div class="site_header__header_four_wrap">
    <div class="topbar-one topbar_four">
      <div class="container">
        <div class="topbar-one__left">
          
        </div>
        <div class="topbar-one__middle">
          <a href="/" class="main-nav__logo">
            <img
              src="/assets/images/resources/frankFull-white.png"
              class="main-logo"
              style="height: 150px;"
              alt="Awesome Image"
            />
          </a>
        </div>
        <div class="topbar-one__right">
          <div class="topbar-one__social">
              <a href="https://www.facebook.com/profile.php?id=100086520483229"><i class="fab fa-facebook-square"></i></a>
              <a href="https://www.instagram.com/franks_livery/"><i class="fab fa-instagram"></i></a>
              <a href="https://twitter.com/franks_livery"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
      </div>
    </div>

    <header class="main-nav__header-one main-nav__header-four">
      
    </header>
  </div>
</template>

<script>
import { mapMutations } from "vuex";

export default {
  name: "NavFour",
  data() {
    return {
      sticky: false,
      mobileToggle: false,
    };
  },
  computed: {
    searchPopup() {
      return this.$store.state.searchPopupStatus;
    },
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      if (window.scrollY > 70) {
        this.sticky = true;
      } else if (window.scrollY < 70) {
        this.sticky = false;
      }
    },
    ...mapMutations({
      searchPopupStatusChange: "changeSearchPopupStatus",
    }),
  },
};
</script>


