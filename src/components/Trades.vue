<template>
  <div class="trade">
    <h3 class="trade-title">{{ title }}</h3>
    <div class="trade-offers">
      <div
        v-for="(offer, index) in offers"
        v-bind:key="index"
        class="trade-offer"
      >
        <a href="#">{{ offer }}</a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Trade",
  props: {
    title: String,
    offers: Array,
  },
};
</script>