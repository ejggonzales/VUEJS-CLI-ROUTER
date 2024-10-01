<template>
  <div class="home">
    <!-- <img src="../assets/logo.png">
    <h1 class="py-4">{{ msg }}</h1> -->

    <!-- Hero -->
    <!-- <div class="p-5 text-center bg-image rounded-3" style="
    background-image: url('../assets/hero-image.jpeg'); 
    height: 400px; background-repeat: no-repeat; background-size: cover;">
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6);">
        <div class="d-flex justify-content-center align-items-center h-100">
          <div class="text-white">
            <h1 class="mb-3">Heading</h1>
            <h4 class="mb-3">Subheading</h4>
            <a data-mdb-ripple-init class="btn btn-outline-light btn-lg" href="#!" role="button">Call to action</a>
          </div>
        </div>
      </div>
    </div> -->
    <!-- Hero -->

    <header class="bg-dark bg-gradient py-5">
      <div class="container px-5">
        <img src="../assets/logo.png" class="mb-3">
        <div class="row gx-5 justify-content-center">
          <div class="col-lg-6">
            <div class="text-center my-5">
              <h1 class="display-4 fw-bolder text-white mb-3">{{ msg }}</h1>
              <p class="lead text-white-50 mb-4">This is my first vuejs project with routing and navigation. Feel free
                to check it out!</p>
              <!-- <div class="d-grid gap-3 d-sm-flex justify-content-sm-center">
                                <a class="btn btn-primary btn-lg px-4 me-sm-3" href="#features">Get Started</a>
                                <a class="btn btn-outline-light btn-lg px-4" href="#!">Learn More</a>
                            </div> -->
            </div>
          </div>
        </div>
      </div>
    </header>

    <!-- <section class="py-5 border-bottom" id="features">
      <div class="container px-5 my-2">
        <h1 class="mb-3">What to find in my VueJS Project?</h1>
        <div class="row gx-5">
          <div class="col-lg-4 mb-5 mb-lg-0">
            <div class="card" style="width: 3rem;">
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <h6 class="card-subtitle mb-2 text-body-secondary">Card subtitle</h6>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
                <a href="#" class="card-link">Card link</a>
                <a href="#" class="card-link">Another link</a>
              </div>
            </div>
          </div>

          <div class="col-lg-4 mb-5 mb-lg-0">
            <div class="card" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <h6 class="card-subtitle mb-2 text-body-secondary">Card subtitle</h6>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
                <a href="#" class="card-link">Card link</a>
                <a href="#" class="card-link">Another link</a>
              </div>
            </div>
          </div>

          <div class="col-lg-4 mb-5 mb-lg-0">
            <div class="card" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <h6 class="card-subtitle mb-2 text-body-secondary">Card subtitle</h6>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
                <a href="#" class="card-link">Card link</a>
                <a href="#" class="card-link">Another link</a>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </section> -->
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: "Welcome to Ethan's Vue.js App"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
