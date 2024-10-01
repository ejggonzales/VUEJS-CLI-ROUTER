<template>
    <div class="blog">
        <h1 class="py-4 fs-1 fw-semibold pt-5">{{ title }}</h1>

        <div class="container mb-5">
            <div class="row row-cols-1 row-cols-md-2 g-4">
                <div class="col">
                    <div class="card">
                        <img src="https://mdbcdn.b-cdn.net/img/new/standard/city/041.webp" class="card-img-top"
                            alt="Hollywood Sign on The Hill" />
                        <div class="card-body">
                            <h5 class="card-title fs-3 fw-bold">Hollywood Chronicles: Behind the Spotlight</h5>
                            <p class="card-text">
                                Delve into the ultimate stories from Tinseltown, exploring the glitz, glam, and untold tales of stars, filmmakers, and the ever-evolving industry. Join us for exclusive insights and behind-the-scenes revelations!
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="https://mdbcdn.b-cdn.net/img/new/standard/city/042.webp" class="card-img-top"
                            alt="Palm Springs Road" />
                        <div class="card-body">
                            <h5 class="card-title fs-3 fw-bold">Peaks of Utah: Mountain Majesty</h5>
                            <p class="card-text">
                                Delve into the ultimate adventures in Utah's stunning mountain ranges, showcasing breathtaking landscapes, outdoor activities, and hidden trails. Explore the natural beauty that makes Utah a paradise for nature lovers!
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="https://mdbcdn.b-cdn.net/img/new/standard/city/043.webp" class="card-img-top"
                            alt="Los Angeles Skyscrapers" />
                        <div class="card-body">
                            <h5 class="card-title fs-3 fw-bold">NYC Unplugged: Urban Adventures</h5>
                            <p class="card-text">Delve into the ultimate experiences in New York City, from hidden gems to iconic landmarks. Discover the vibrant culture, culinary delights, and unique stories that make the Big Apple unforgettable!</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="https://mdbcdn.b-cdn.net/img/new/standard/city/044.webp" class="card-img-top"
                            alt="Skyscrapers" />
                        <div class="card-body">
                            <h5 class="card-title fs-3 fw-bold">Skyline Stories: Atlanta's Architectural Gems</h5>
                            <p class="card-text">
                                Explore the fascinating blend of history and modernity in Atlanta's skyline. From iconic skyscrapers to historic landmarks, discover the stories behind the city's most captivating buildings and the architects who shaped them.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
  <script>
  export default {
    name: 'blog',
    data () {
      return {
          title: "Here are my sample Blogs!"
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
  