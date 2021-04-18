<template>
  <div>
    <Navbar />
    <h1>Welcome to Goals Site <span>&#127919;</span></h1>
    <button>start your journey</button>
    <Footer />
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Footer from '../components/Footer.vue'
export default {
  components: {
    Navbar,
    Footer,
  },
}
</script>

<style scoped>
html,
body {
  font-family: 'Roboto', sans-serif;
  width: 100%;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
h1 {
  color: black;
  text-align: center;
  font-size: 2.5em;
  margin-top: 0.9em;
  font-weight: 700;
}
button {
  color: #ffffff;
  background-color: #1d1283;
  text-align: center;
  font-size: 1.3em;
  padding: 0.5em;
  border: none;
  outline: none;
  border-radius: 0.2em;
  text-transform: capitalize;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  cursor: pointer;
}
</style>
