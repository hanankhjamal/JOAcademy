<template>
  <v-app style="direction: rtl;font-family: 'NotoKufiArabic', sans-serif !important">
    <Header />

    <v-content>
      <NavigationDrawer />
      <Container />
    </v-content>
    <Footer />
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import NavigationDrawer from "./components/NavigationDrawer";
import Header from "./components/Header";
import Container from "./components/Container";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    Header,
    NavigationDrawer,
    Container,
    Footer
  },
  data: () => ({
    //
  })
};
</script>

<style scoped>
@font-face {
  font-family: "NotoKufiArabic";
  src: url(//fonts.gstatic.com/ea/notokufiarabic/v2/NotoKufiArabic-Regular.woff2);
  font-weight: normal;
  font-style: normal;
}
</style>
