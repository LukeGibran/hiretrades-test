<template>
  <section class="section">
    <div class="container">
      <div class="main-column sectionSix">
        <div class="section-title">
          <h2>Our Top Trades</h2>
        </div>

        <div class="trades">
          <Trades title="Sydney" :offers="Sydney" />
          <Trades title="Melbourne" :offers="Melbourne" />
          <Trades title="Brisbane" :offers="Brisbane" />
          <Trades title="Perth" :offers="Perth" />
          <Trades title="Adelaide" :offers="Adelaide" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Trades from "../../../components/Trades";
export default {
  name: "SectionSix",
  components: { Trades },
  data() {
    return {
      Sydney: [
        " Painters",
        "Pest Control",
        "Electricians",
        "Plumbers",
        "Concreting",
        "Carpenters",
      ],
      Melbourne: [
        "Handyman",
        "Electricians",
        "Concreting",
        "Painters",
        "Plumbers",
        "Bricklaying",
      ],
      Brisbane: [
        "Pest Control",
        "Painters",
        "Fencing",
        "Handyman",
        "Electricians",
        "Air Conditioning",
      ],
      Perth: [
        " Plumbers",
        "Painters",
        "Carpenters",
        "Electricians",
        "Air Conditioning",
        "Kitchen",
      ],
      Adelaide: [
        "Painters",
        "Fencing",
        "Builder",
        "Electricians",
        "Handyman",
        "Air Conditioning",
      ],
    };
  },
};
</script>