<template>
  <div class="home">
    <p>Hey 👋 I'm Brad.</p>
    <img alt="Profile image" src="../assets/profile.jpg" />

    <p>💻 I'm a Web Developer</p>

    <p>🏠 Based in Stockport</p>

    <p>I like to use languages such as JS, TS, Node, Express, VueJS & PHP.</p>

    <p>
      Check out my
      <a href="https://github.com/rocstack" target="_blank">GitHub</a> 🔗
    </p>

    <p>This page is still in construction 🏗️ stuff looks very wonky.</p>

    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->

    <br />
    <p>You can see some of my work below (TBA):</p>

    <div class="my-work-container">
      <div class="my-work-item">1</div>
      <div class="my-work-item">2</div>
      <div class="my-work-item">3</div>
      <div class="my-work-item">4</div>
      <div class="my-work-item">5</div>
      <div class="my-work-item">6</div>
      <div class="my-work-item">7</div>
      <div class="my-work-item">8</div>
      <div class="my-work-item">9</div>
      
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
  },
};
</script>

<style lang="scss">
img {
  border-radius: 50%;
}
a {
  color: white;
}
.my-work-container {
  display: grid;
  grid-template-columns: auto auto auto;
  padding: 10px;
}
.my-work-item {
  border: 1px solid rgba(0, 0, 0, 0.8);
  padding: 20px;
  font-size: 30px;
  text-align: center;
}
</style>
