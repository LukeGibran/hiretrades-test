<template>
  <div :class="cardClass">
    <img
      :src="require(`@/assets/${image}`)"
      alt=""
      class="card-image"
      v-if="!rightSideImage"
    />
    <div class="card-info">
      <h3 class="card-title">{{ title }}</h3>
      <p class="card-description">
        {{ desc }}
      </p>
      <div class="card-link">
        <a href="#" class="link">{{ link }}</a>
      </div>
    </div>
    <img
      :src="require(`@/assets/${image}`)"
      alt=""
      class="card-image"
      v-if="rightSideImage"
    />
  </div>
</template>
<script>
export default {
  name: "Card",
  props: {
    cardClass: String,
    rightSideImage: {
      type: Boolean,
      default: false,
    },
    image: String,
    title: String,
    desc: String,
    link: String,
  },
};
</script>