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
      <div class="my-work-item">
        <h4>Torch CRM</h4>
        <p>This is a CRM/Business space web app for managing business relations (employees, companies), creating tasks and deloying code to servers.</p>
      </div>

      <div class="my-work-item">
        <h4>Project Boxing</h4>
        <p>A boxing simulation game built in Unity3D and scripting in C#. This game has been accepted by steam marketplace.</p>
      </div>

      <div class="my-work-item">
        <h4>Torchl (torchl.com)</h4>
        <p>A website creation tool for simplifying making a website and hosting it.</p>
      </div>
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
  text-align: center;
}
</style>
