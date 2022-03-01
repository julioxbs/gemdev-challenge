<template>
  <Nav />
  <Hero />
  <Statement />
  <Details />
  <Features />
  <About />
  <Counter />
  <Inventation />
  <Contact />
  <Footer />
</template>

<script>
import Nav from './components/Nav.vue';
import Hero from './components/Hero.vue';
import Statement from './components/Statement.vue';
import Details from './components/Details.vue';
import Features from './components/Features.vue';
import About from './components/About.vue';
import Counter from './components/Counter.vue';
import Inventation from './components/Inventation.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
export default {
  components: {
    Nav, Hero,
    Statement, Details,
    Features, About,
    Counter, Inventation,
    Contact, Footer,
  }
}
</script>