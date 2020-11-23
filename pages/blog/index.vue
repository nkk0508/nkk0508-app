<template>
  <div class="container">
    <div>
      <h1 class="title">
        nkk0508
      </h1>
      <div class="links">
        <div class="home-link">
          <a href="http://localhost:3000">
            Home
          </a>
        </div>
        <div class="blog-link">
          <a href="http://localhost:3000/blog">
            Blog
          </a>
        </div>
        <div class="github-link">
          <a href="https://github.com/nkk0508">
            GitHub
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #35495e;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
  color: white;
}

a {
  text-decoration:none;
  color: white;
  margin: 10px;
}

.blog-link {
  margin: 10px;
}
</style>
