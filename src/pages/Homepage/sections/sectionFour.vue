<template>
  <section class="section">
    <div class="container">
      <div class="main-column sectionFour">
        <div class="section-title">
          <h2>What homeowners are saying</h2>
        </div>

        <div class="boxes">
          <Box
            image="jodie.webp"
            story="You make life really easy for last minute people like me. I'm always time challenged and not wanting to spend the time chasing Tradies. Two minutes to post a job. Right price, right quality, right timing. No stress whatsoever. Thanks HIREtrades."
            name="Jodie, NSW"
          />
          <Box
            image="kenvacation.webp"
            story="This has to be the best way to go. Goodbye to searching the internet for hours or fumbling through business directories. HIREtrades do it all for me and it only take a couple of minutes to post the job. Great work guys"
            name="Tony, WA"
          />
          <Box
            image="joseph-sydney.webp"
            story="I can refurbish my entire kitchen sourcing the trades from HIREtrades. Plumbers, electricians, cabinet-makers, tilers, floor coverings and painters – it is so convenient. Saves me time and money. I get all the Quotes for free and the app is really easy to use. You can count on my repeat business."
            name="Keith, NSW"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Box from "../../../components/Box";
export default {
  name: "SectionFour",
  components: {
    Box,
  },
};
</script>