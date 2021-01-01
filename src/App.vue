<template>
  <div id="app">
    <Header />
    <Signup />
    <About />
    <Features />
    <Plans />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header';
import Signup from './components/Signup';
import About from './components/About';
import Features from './components/Features';
import Plans from './components/Plans';
import Footer from './components/Footer';


export default {
  name: 'App',
  components: {
   Header,
   Signup,
   About,
   Features,
   Plans,
   Footer
  },
   data () {
        return {
        showsignup: true,
        lastScrollPosition: 0
        }
    },
    mounted () {
        window.addEventListener('scroll', this.onScroll)
    },
    beforeUnmount () {
        window.removeEventListener('scroll', this.onScroll)
    },
    methods: {
        onScroll () {
            // Get the current scroll position
            const currentScrollPosition = window.pageYOffset || document.documentElement.scrollTop
            // Because of momentum scrolling on mobiles, we shouldn't continue if it is less than zero
            if (currentScrollPosition < 0) {
                return
            }
            // Here we determine whether we need to show or hide the navbar
            this.showsignup = currentScrollPosition < this.lastScrollPosition
            // Set the current scroll position as the last scroll position
            this.lastScrollPosition = currentScrollPosition
        }
}
}
</script>

<style>
 
</style>
