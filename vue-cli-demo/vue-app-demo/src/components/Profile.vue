<template>
    <div id="profile">
        <div id="todo-card">
            <div class="container">
                <!-- <div class="alert alert-primary" role="alert">
                  <h1>{{ msg6 }}</h1>
              </div> -->
                <section class="w-100 mb-3 px-4 py-4" style="background-color: #F5F5F7; border-radius: .5rem .5rem 0 0;">
                    <div class="row d-flex justify-content-center">
                        <h3 class="text-uppercase fs-1 fw-bold">My Profile</h3>
                        <div class="col col-md-9 col-lg-7 col-xl-9">
                            <div class="card mt-3" style="border-radius: 15px;">
                                <div class="card-body p-3">
                                    <div class="d-flex">
                                        <div class="flex-shrink-0">
                                            <img src="../assets/Profilepic.png" alt="Generic placeholder image"
                                                class="img-fluid" style="width: 320px; border-radius: 10px;">
                                        </div>
                                        <div class="flex-grow-1 ms-3 my-3 text-start">
                                            <h5 class="mb-1 fs-3 ps-4 fw-bold">Ethan James G. Gonzales</h5>
                                            <p class="mb-2 pb-1 fs-4 ps-4 fw-semibold">3rd Year Web Development Student</p>
                                            <p class="mb-1 fs-5 ps-4 ">Email: ethanjamesgonzales088@gmail.com</p>
                                            <p class="mb-1 fs-5 ps-4 ">Contact Info: 0999-999-9999</p>
                                            <p class="mb-1 fs-5 ps-4 ">Address: Madapdap, Mabalacat City, Pampanga</p>
                                            <p class="mb-1 fs-5 ps-4 ">Birthdate: April 24, 2004</p>
                                            <p class="mb-1 fs-5 ps-4 ">Age: 20 years old</p>
                                            <p class="mb-1 fs-5 ps-4 ">Nationality: Filipino</p>
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
    name: 'profile',
    data () {
      return {
        msg6: 'This is the Profile component'
      }
    }
  }
  </script>
  
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

  #app {
    /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
    font-family: 'Poppins', sans-serif;
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
  