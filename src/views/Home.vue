<template>
  <div class="home">
    <HeaderShayna />
    <CarouselShayna />
    <ProductSlider />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import CarouselShayna from "@/components/CarouselShayna.vue";
import ProductSlider from "@/components/ProductSlider.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    CarouselShayna,
    ProductSlider,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
};
</script>
