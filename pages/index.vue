<template>
  <div id="root">
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
    />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous"></link>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,400;0,700;1,400&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display+SC:wght@700&display=swap" rel="stylesheet">
    <Header/>
    <Banner/>
    <about-us/>
    <contact-us/>
    <Footer/>
    <BackToTopBtn/>
  </div>
</template>

<script>
import AboutUs from '../components/AboutUs.vue';
import BackToTopBtn from '../components/BackToTopBtn.vue';
import ContactUs from '../components/ContactUs.vue';
import Footer from '../components/Footer.vue';
import Header from "../components/Header.vue";
export default {
  components: { Header, ContactUs, Footer, AboutUs, BackToTopBtn },
  name: "IndexPage",
};
</script>
