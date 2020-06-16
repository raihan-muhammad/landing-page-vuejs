<template>
  <div id="app">
    <Navbar />
    <HeaderHome />
    <FiturBrand />
    <PaketHosting />
    <FiturPHP />
    <FiturDua />
    <FiturLaravel />
    <Module />
    <LinuxHosting />
    <Sosmed />
    <Bantuan />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HeaderHome from "./components/HeaderHome.vue";
import FiturBrand from "./components/FiturBrand.vue";
import PaketHosting from "./components/PaketHosting.vue";
import FiturPHP from "./components/FiturPHP.vue";
import FiturDua from "./components/FiturDua.vue";
import FiturLaravel from "./components/FiturLaravel.vue";
import Module from "./components/Module.vue";
import LinuxHosting from "./components/LinuxHosting.vue";
import Sosmed from "./components/Sosmed.vue";
import Bantuan from "./components/Bantuan.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    HeaderHome,
    FiturBrand,
    PaketHosting,
    FiturPHP,
    FiturDua,
    FiturLaravel,
    Module,
    LinuxHosting,
    Sosmed,
    Bantuan,
    Footer,
  },
};
</script>
