<template>
  <div class="container">
    <Sidebar />
    <Header />
    <Realtors />
    <Features />
    <div class="story__pictures">
      <img src="../assets/img/story-1.jpeg" alt="Couple with a new house" class="story__img--1" />
      <img src="../assets/img/story-2.jpeg" alt="Couple with a new house" class="story__img--2" />
    </div>
    <div class="story__content">
      <h3 class="heading-3 mb-sm">Happy Customers</h3>
      <h2 class="heading-2 heading-2--dark mb-md">&ldquo;The Best decision of our lives&rdquo;</h2>
      <p
        class="story__text"
      >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facilis fugit corrupti blanditiis, repellat illum commodi. Voluptatem quam inventore fuga, vel est reiciendis, fugit a, culpa enim corporis natus harum et.</p>
      <button class="btn">Find your own home</button>
    </div>
    <HomeComponent />
    <Gallery />
    <Footer />
  </div>
</template>
<script>
import Sidebar from "@/components/SidebarComponent";
import Header from "@/components/HeaderComponent";
import Realtors from "@/components/RealtorsComponent";
import Features from "@/components/FeaturesComponent";
import HomeComponent from "@/components/HomeComponent";
import Gallery from "@/components/GalleryComponent";
import Footer from "@/components/FooterComponent";
export default {
  name: "Home",
  components: {
    Sidebar,
    Header,
    Realtors,
    Features,
    HomeComponent,
    Gallery,
    Footer
  }
};
</script>
