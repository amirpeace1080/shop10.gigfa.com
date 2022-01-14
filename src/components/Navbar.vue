<template>
  <header>
    <div class="header">
      <div class="logo">
        <img src="./../../public/images/logo.png" alt="logo" />
      </div>
      <nav class="desktop-nav">
        <ul class="menu">
          <li class="menu-item">
            <a href="#" class="menu-link">{{ $t("navbar.men_fashion") }}</a>
          </li>
          <li class="menu-item">
            <a href="#" class="menu-link">{{ $t("navbar.women_ashion") }}</a>
          </li>
          <li class="menu-item">
            <a href="#" class="menu-link">{{ $t("navbar.beauty") }}</a>
          </li>
          <li class="menu-item">
            <a href="#" class="menu-link">{{ $t("navbar.daily_needs") }}</a>
          </li>
          <li class="menu-item">
            <a
              href="#"
              class="menu-link-language"
              @click.prevent="changeLocale"
            >
              {{ currentLocale }}
            </a>
          </li>
        </ul>
      </nav>
      <nav class="mobile-nav">
        <div class="mobile-nav-icon">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </nav>
      <div class="cart">
        <img src="./../../public/images/carticon.png" alt="cart" />
      </div>
    </div>
    <div class="slider">
      <img src="./../../public/images/slide.jpg" alt="slider" />
      <div class="slider-text">
        <h1>
          {{ $t("navbar.latest_fashion") }} <br />{{ $t("navbar.collection") }}
        </h1>
        <p>
          {{ $t("navbar.set_ut") }}
        </p>
        <a href="#">{{ $t("navbar.explore") }}</a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Navbar",
  computed: {
    currentLocale() {
      return this.$i18n.locale === "fa" ? "فارسی" : "English";
    },
  },
  methods: {
    changeLocale() {
      this.$i18n.locale = this.$i18n.locale === "fa" ? "en" : "fa";
    },
  },
};
</script>

<style></style>
