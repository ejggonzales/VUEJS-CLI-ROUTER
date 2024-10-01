<template>
    <div class="contact">
        <h1 class="py-4 fs-1 fw-semibold pt-5">{{ msg }}</h1>

        <div class="container contact-icons pb-4" style="background-color: #C4DAD2; border-radius: .5rem .5rem 0 0;">
            <div class="text-center mt-2 pt-4">
                <div class="row">
                    <div class="col-lg-3 col-md-6 mb-5 mb-md-5 mb-lg-0 position-relative">
                        <i class="fa-solid fa-phone-volume fa-4x mb-4"></i>
                        <h5 class="text-dark fw-bold mb-3">Phone Number</h5>
                        <h6 class="fw-normal mb-0">0998 292 9420</h6>
                        <div class="vr vr-blurry position-absolute my-0 h-100 d-none d-md-block top-0 end-0"></div>
                    </div>

                    <div class="col-lg-3 col-md-6 mb-5 mb-md-5 mb-lg-0 position-relative">
                        <i class="fa-solid fa-envelope-open-text fa-4x mb-4"></i>
                        <h5 class="text-dark fw-bold mb-3">Email Address</h5>
                        <h6 class="fw-normal mb-0">ethanjamesgonzales088@gmail.com</h6>
                        <div class="vr vr-blurry position-absolute my-0 h-100 d-none d-md-block top-0 end-0"></div>
                    </div>

                    <div class="col-lg-3 col-md-6 mb-5 mb-md-0 position-relative">
                        <i class="fa-brands fa-facebook fa-4x mb-4"></i>
                        <h5 class="text-dark fw-bold mb-3">Facebook Page</h5>
                        <h6 class="fw-normal mb-0">facebook.com/ethan.gonzales.731/</h6>
                        <div class="vr vr-blurry position-absolute my-0 h-100 d-none d-md-block top-0 end-0"></div>
                    </div>

                    <div class="col-lg-3 col-md-6 mb-5 mb-md-0 position-relative">
                        <i class="fa-brands fa-square-instagram fa-4x mb-4"></i>
                        <h5 class="text-dark fw-bold mb-3">Instagram Page</h5>
                        <h6 class="fw-normal mb-0">_tanjeyms</h6>
                    </div>
                </div>
            </div>

        </div>
        <h1 class="pt-4 fs-2 fw-bold">Ask me anything if you have any questions!</h1>
    </div>
</template>
  
  <script>
  export default {
    name: 'contact',
    data () {
      return {
        msg: "Here are my Contact Details!"
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
  