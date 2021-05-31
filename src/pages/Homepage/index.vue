<template>
  <Navbar />
  <SectionOne />
  <SectionTwo />
  <SectionThree />
  <SectionFour />
  <SectionFive />
  <SectionSix />
  <Footer />
</template>

<script>
import Navbar from "../../components/Navbar";
import SectionOne from "./sections/sectionOne";
import SectionTwo from "./sections/sectionTwo";
import SectionThree from "./sections/sectionThree";
import SectionFour from "./sections/sectionFour";
import SectionFive from "./sections/sectionFive";
import SectionSix from "./sections/sectionSix";
import Footer from "../../components/Footer";
export default {
  name: "Home",
  components: {
    Navbar,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
    SectionSix,
    Footer,
  },
};
</script>