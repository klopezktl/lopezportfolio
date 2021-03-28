<template>
  <section id="home" class="home">
    <Top />
    <Jumbotron />
    <Introduction />
    <Experience />
    <Skills />
    <Education />
    <Footer />
  </section>


</template>

<script>
import Top from '../components/Top.vue'
import Jumbotron from '../components/Jumbotron.vue'
import Introduction from '../components/Introduction.vue'
import Experience from '../components/Experience.vue'
import Skills from '../components/Skills.vue'
import Education from '../components/Education.vue'
import Footer from '../components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Top,
    Jumbotron,
    Introduction,
    Experience,
    Skills,
    Education,
    Footer
  }
}

</script>

<style>

h1 {
  margin: 0 0 !important;
  text-align: center;
  font-family: 'Montserrat', sans-serif;
  font-size: 50px !important;
  font-weight: 900 !important;
}

h2 {
  color: #A9EEE6;
  font-family: 'Montserrat', sans-serif;
  font-weight: 600;
  text-align: center;
  padding-bottom: 20px;
  font-size: 40px;
}

h3 {
  color: #A9EEE6;
  font-family: 'Montserrat', sans-serif;
  font-size: 20px;
  font-weight: bolder;
}

.greeting{
  color: #FEFAEC;
  text-align: right;
  /* background-color: #625772; */
  font-size: 130px;
  padding: 150px 100px 0;
  font-family: 'Montserrat', sans-serif;
  line-height: 0.8;
  font-weight: 900;
}

.jumbotron {
  background-image: url('../assets/background02.png');
  background-size: cover;
  /* height: 764px; */
  height: 790px;
  margin-bottom: 0 !important;
}

.title {
  background-color: #FEFAEC;
  color: #625772;
  padding: 20px 100px 0;
  text-align: center;
  border: 0;
}

/* /fixed this later */

.home {
  /* background-color: #FEFAEC; */
}

.colored-section {
  background-color: #625772;
  color:#FEFAEC;
  padding: 100px 100px;
}

.white-section {
  color: #625772;
  background-color: #FEFAEC;
  /* background-color: green; */
  padding: 100px 100px;
}

.white-section h2,
.white-section h3,
.white-section h4 {
  color: #625772;
}

.location {
  font-weight: bolder;
}

</style>
