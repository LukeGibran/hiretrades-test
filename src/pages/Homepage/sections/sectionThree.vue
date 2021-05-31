<template>
  <section class="section">
    <div class="container">
      <div class="main-column sectionThree">
        <div class="section-title">
          <h2>Inspirational Panel</h2>
        </div>

        <div class="cards">
          <div class="left-card">
            <Card
              cardClass="card horizontal"
              title="Cost Guides"
              desc="Research to assist consumers with Trades pricing."
              link="View prices"
              image="accounting-balance-banking.webp"
            />
            <Card
              cardClass="card horizontal"
              title="Blogs"
              desc="Articles of interest and gread ideas."
              link="Discover more"
              image="organise.webp"
              :rightSideImage="true"
            />
          </div>
          <div class="right-card">
            <Card
              cardClass="card vertical"
              title="Ask a Tradie"
              desc="Our network of Tradies can help answer your question"
              link="What's your question?"
              image="blueprint-designing-diagram.webp"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Card from "../../../components/Card";
export default {
  name: "SectionThree",
  components: {
    Card,
  },
};
</script>