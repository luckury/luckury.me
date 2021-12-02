<template>
  <div class="container">
    <div class="hello">
        <h1>Hello,</h1>
    </div>
    <div class="description">
        <h1>I'm Luc Kury, a <span class="highlight">software developer/engineer</span> based in <span class="underline">Basel</span>.</h1>
    </div>
    <p class="description">I enjoy working on software projects. Be it a frontend, a backend, an open-source or a business application. I'm interested in technologies like Kubernetes, Docker, CI/CD, SPA, etc.</p>
  </div>
</template>

<script>
export default {
  name: 'Hello'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
    font-size: 4rem;
}

.container {
  width: 40%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 98vh;
  margin-left: 15rem;
}

.description {
  line-height: 1.5;
}

.highlight {
  background: #ff9f1c;
  padding: 0.5rem
}

.underline {
  text-decoration: underline;
  text-decoration-color: #ff9f1c;
  text-underline-offset: 0.5rem;
}
</style>
