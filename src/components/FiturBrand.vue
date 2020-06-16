<template>
  <section class="container">
    <div class="row align-items-end justify-content-md-center fitur-brand">
      <FiturBrandItem
        caption="PHP Zend Guard Loaders"
        images="zenguard.png"
        classGambar="img-zenguard"
      />
      <FiturBrandItem
        caption="PHP Zend Guard Loaders"
        images="composer.png"
        classGambar="img-composer"
      />
      <FiturBrandItem
        caption="PHP Zend Guard Loaders"
        images="ioncube.png"
        classGambar="img-ioncube"
      />
    </div>
  </section>
</template>

<script>
import FiturBrandItem from "./FiturBrandItem.vue";
export default {
  name: "FiturBrand",
  components: {
    FiturBrandItem,
  },
};
</script>
