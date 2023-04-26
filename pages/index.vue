<template>
  <div>
    <NavFour />
    <SliderFour />
    <DetailsOne />
    <WelcomeTwo />
    <EcoFriendly />
    <ContactTwo />
    <!-- <ServiceFour /> -->
    <!-- <FaqOne /> -->
    <!-- <TestimonialThree /> -->
    <!-- <BrandFour /> -->
    <!-- <AchievedOne /> -->
    <!-- <FunfactOne />
    <BlogFour /> -->
    <!-- <Footer /> -->
    <div class="footer-wrapper">
      <div class="footer-links">
        <a
          href="/assets/pdfs/FPAclientEmergencyPlan.pdf"
          download
          class="frank-btn-two"
          >FPA Emergency Plan</a
        >
        <a
          href="/assets/pdfs/FPLpaddilingEthicsSaftey.pdf"
          download
          class="frank-btn-two"
          >FPL Paddling Ethics and Safety</a
        >
      </div>
    </div>
  </div>
</template>

<script>
import SliderFour from "../components/SliderFour";
import NavFour from "../components/NavFour";
import DetailsOne from "../components/DetailsOne";
import WelcomeTwo from "../components/WelcomeTwo";
import EcoFriendly from "../components/EcoFriendly";
import ServiceFour from "../components/ServiceFour";
import FaqOne from "../components/FaqOne";
import TestimonialThree from "../components/TestimonialThree";
import BrandFour from "../components/BrandFour";
import AchievedOne from "../components/AchievedOne";
import FunfactOne from "../components/FunfactOne";
import BlogFour from "../components/BlogFour";
import Footer from "../components/Footer";
import ContactTwo from "../components/ContactTwo";
export default {
  components: {
    Footer,
    BlogFour,
    FunfactOne,
    AchievedOne,
    BrandFour,
    TestimonialThree,
    FaqOne,
    ServiceFour,
    EcoFriendly,
    WelcomeTwo,
    DetailsOne,
    NavFour,
    SliderFour,
    ContactTwo
  },
  head() {
    return {
      title: "Frank's Paddlesports Livery"
    };
  }
};
</script>
<style lang="css" scoped>
.footer-wrapper {
  background-color: #fffbce;
  padding-left: 25px;
  padding-right: 25px;
}
.footer-links {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  height: 100%;
  color: #3b4a25 !important;
}
.footer-links a {
  color: #3b4a25 !important;
}
</style>
```
