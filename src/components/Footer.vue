<template>
  <footer>
    <div class="container">
      <div class="footer-heading">
        <h3>{{ $t("footer.subscribe_to_newsletters") }}</h3>
        <p>{{ $t("footer.lorem1") }} <br />{{ $t("footer.lorem2") }}</p>
      </div>
      <div class="subscribe-button">
        <form action="" method="POST">
          <input type="email" :placeholder="$t('footer.your_email_address')" />
          <input type="submit" :value="$t('footer.subscribe')" />
        </form>
      </div>
      <nav>
        <ul class="footer-navbar">
          <li>
            <a href="#">{{ $t("footer.about_us") }}</a>
          </li>
          <li>
            <a href="#">{{ $t("footer.faq") }}</a>
          </li>
          <li>
            <a href="#">{{ $t("footer.contact_us") }}</a>
          </li>
          <li>
            <a href="#">{{ $t("footer.privacy_policy") }}</a>
          </li>
          <li>
            <a href="#">{{ $t("footer.terms_of_services") }}</a>
          </li>
        </ul>
      </nav>
      <p class="copyright">
        Copyright &#x24B8; 2022 Fashion. All Rights Reserved.
      </p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style></style>
