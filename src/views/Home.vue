<template>
  <main>
    <section class="products">
      <div class="heading">
        <h2>{{ $t("home.latest_products") }}</h2>
        <p>{{ $t("home.everything_that_new") }}</p>
      </div>
      <div class="products-item">
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item1.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.ethinik_dresses") }}</h5>
            <p><del>$250.00</del>$199.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item2.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.active_T_shirts") }}</h5>
            <p><del>$340.00</del>$299.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item3.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.another_T_shirts") }}</h5>
            <p><del>$100.00</del>$99.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item4.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.harpa_T_shirts") }}</h5>
            <p><del>$350.00</del>$255.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item5.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.harpa_T_shirts") }}</h5>
            <p><del>100.00</del>$99.00</p>
          </div>
        </div>
        <div class="item">
          <div class="button item-image">
            <img src="./../../public/images/item6.jpg" />
            <div class="item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.double_clothes") }}</h5>
            <p><del>$100.00</del>$99.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item7.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.active_T_shirts") }}</h5>
            <p><del>$55.00</del>$35.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item8.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.full_T_shirts") }}</h5>
            <p><del>$250.00</del>$150.00</p>
          </div>
        </div>
      </div>
      <div class="button viewAll-button">
        <a href="#">{{ $t("home.view_all_items") }}</a>
      </div>
    </section>
    <section class="banner newArrivals-bg">
      <h3 class="banner-tittle">{{ $t("home.new_summer") }}</h3>
      <div class="button banner-button">
        <a href="#">{{ $t("home.get_it_now") }}</a>
      </div>
    </section>
    <section class="fetured-products">
      <div class="heading">
        <h2>{{ $t("home.fetured_products") }}</h2>
        <p>{{ $t("home.everything_that_new") }}</p>
      </div>
      <div class="products-item">
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item9.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.harpa_T_shirts") }}</h5>
            <p>$199.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item10.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.harpa_dresses") }}</h5>
            <p>$199.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item11.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.new_dresses") }}</h5>
            <p>$99.00</p>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item12.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.add_to_cart") }}</a>
              <a href="#">{{ $t("home.quick_view") }}</a>
            </div>
          </div>
          <div class="item-title">
            <h5>{{ $t("home.hot_dresses") }}</h5>
            <p>$255.00</p>
          </div>
        </div>
        <div class="button viewAll-button">
          <a href="#">{{ $t("home.view_all_items") }}</a>
        </div>
      </div>
    </section>
    <section class="banner feturedProducts-bg">
      <div class="button banner-button-brand">
        <a href="#"></a>
        <a href="#"></a>
        <a href="#"></a>
        <a href="#"></a>
        <a href="#"></a>
      </div>
    </section>
    <section class="amazing-products">
      <div class="heading">
        <h2>{{ $t("home.our_amazing_products") }}</h2>
        <p>{{ $t("home.everything_that_new") }}</p>
      </div>
      <div class="products-item">
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item13.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.see_more") }}</a>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item14.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.see_more") }}</a>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item15.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.see_more") }}</a>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="item-image">
            <img src="./../../public/images/item16.jpg" />
            <div class="button item-button">
              <a href="#">{{ $t("home.see_more") }}</a>
            </div>
          </div>
        </div>
        <div class="button viewAll-button">
          <a href="#">{{ $t("home.view_all_items") }}</a>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "Home",
};
</script>
