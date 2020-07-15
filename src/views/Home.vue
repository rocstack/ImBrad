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
      <div class="my-work-item">CRM Frontend</div>
      <div class="my-work-item">CRM API</div>
      <div class="my-work-item">Project Boxing</div>
      <div class="my-work-item">Torch System</div>
      <div class="my-work-item">Trintiy</div>
      <div class="my-work-item">Buzz</div>
      <div class="my-work-item">RagdollMan</div>
      <div class="my-work-item">InsAPI</div>
      <div class="my-work-item">-</div>
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
