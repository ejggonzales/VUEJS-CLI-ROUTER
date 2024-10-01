<template>
    <div id="skill">
      <div id="todo-card">
          <div class="container">
            <section class="w-100 mb-3 px-4 py-4" style="background-color: #F5F5F7; border-radius: .5rem .5rem 0 0;">
                    <div class="row d-flex justify-content-center">
                        <h3 class="text-uppercase fs-1 fw-bold">My Skills</h3>
                        <div class="col col-md-9 col-lg-7 col-xl-9">
                            <div class="card mt-3" style="border-radius: 15px;">
                                <div class="card-body p-3">
                                    <div class="d-flex">
                                        <!-- <div class="flex-shrink-0">
                                            <img src="../assets/Profilepic.png" alt="Generic placeholder image"
                                                class="img-fluid" style="width: 320px; border-radius: 10px;">
                                        </div> -->
                                        <div class="flex-grow-1 ms-3 my-3 text-start">
                                            <div class="mb-4">
                                                <p class="mb-1 fs-4 ps-4 fw-semibold">Soft Skills:</p>
                                                <p class="mb-1 fs-5 ps-4 ">Can collaborate or work properly with others</p>
                                                <p class="mb-1 fs-5 ps-4 ">Has a lot of technical knowledge</p>
                                                <p class="mb-1 fs-5 ps-4 ">Can keep up with rapidly evolving technologies</p>
                                                <p class="mb-1 fs-5 ps-4 ">Has great communication skills</p>
                                                <p class="mb-1 fs-5 ps-4 ">Can manage time properly</p>
                                            </div>

                                            <div>
                                                <p class="mb-1 fs-4 ps-4 fw-semibold">Learned Programming Languages:</p>
                                                <p class="mb-1 fs-5 ps-4 ">HTML, CSS, Javascript, Python, Java</p>
                                            </div>
                                        
                                            <!-- <div
                                                class="d-flex justify-content-start rounded-3 p-2 mb-2 bg-body-tertiary">
                                                <div>
                                                    <p class="small text-muted mb-1">Articles</p>
                                                    <p class="mb-0">41</p>
                                                </div>
                                                <div class="px-3">
                                                    <p class="small text-muted mb-1">Followers</p>
                                                    <p class="mb-0">976</p>
                                                </div>
                                                <div>
                                                    <p class="small text-muted mb-1">Rating</p>
                                                    <p class="mb-0">8.5</p>
                                                </div>
                                            </div>
                                            <div class="d-flex pt-1">
                                                <button  type="button" data-mdb-button-init data-mdb-ripple-init class="btn btn-outline-primary me-1 flex-grow-1">Chat</button>
                                        <button  type="button" data-mdb-button-init data-mdb-ripple-init class="btn btn-primary flex-grow-1">Follow</button>
                                            </div> -->
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </section>
          </div>
      </div>
      
    </div>
  </template>
  
  <script>
  export default {
    name: 'skill',
    data () {
      return {
        msg6: 'This is the Skill component'
      }
    }
  }
  </script>
  
  <style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  
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
  