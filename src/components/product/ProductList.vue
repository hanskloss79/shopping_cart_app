<template>
  <div id="products" class="box">
    <div class="products--header has-text-centered">
      <i class="fa fa-2x fa-user-circle"></i>
    </div>
    <div class="product-list">
      <div class="product-list--item">
        <div>
          <h2 class="has-text-weight-bold">Bluza z kapturem
            <span class="tag 
                is-primary
                is-pulled-right
                has-text-white">
              Dodaj do koszyka
            </span>
          </h2>
          <p>Lekka, oddychająca bluza z kapturem z logo Vue.
           Gwarantujemy, że będziesz wyglądać świeżo, gdy jest gorąco.</p>
          <span class="has-text-primary has-text-weight-bold">
            <i class="fa fa-pln"></i> 200 zł
          </span>
        </div>
      </div>
    </div>
    <div class="product-count has-text-right">
      <span class="has-text-weight-bold">Liczba produktów: 4</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProductList',
}
</script>

<style scoped>
.tag {
  cursor: pointer;
}

.products--header {
  border-bottom: 1px solid #E8E8E8;
  padding-bottom: 15px;
}

.product-list {
  padding-top: 10px;
}

.product-list--item {
  padding: 10px 0;
}
</style>
