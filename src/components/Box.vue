<template>
  <div class="box">
    <div class="box-content">
      <img :src="require(`@/assets/${image}`)" alt="" class="box-image" />
      <p class="box-story">"{{ story }}"</p>
      <h4 class="box-name">{{ name }}</h4>
    </div>
  </div>
</template>
<script>
export default {
  name: "Box",
  props: {
    image: String,
    story: String,
    name: String,
  },
};
</script>