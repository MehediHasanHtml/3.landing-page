<template>
  <section class="header-area">
     <div class="container">
        <div class="row">
           <div class="col-12">
              <nav class="navbar navbar-expand-lg">
                 <div class="container-fluid">
                    <a class="navbar-brand" href="#">Launch<span class="dot">.</span></a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                       <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                          <li class="nav-item">
                             <a class="nav-link active" aria-current="page" href="#">Home</a>
                          </li>
                          <li class="nav-item">
                             <a class="nav-link" href="#">Link</a>
                          </li>
                          <li class="nav-item dropdown">
                             <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                             Dropdown
                             </a>
                             <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Testimonials</a></li>
                                <li><a class="dropdown-item" href="#">Menu Two</a></li>
                                <li><a class="dropdown-item" href="#">Menu Three</a></li>
                             </ul>
                          </li>
                          <li class="nav-item">
                             <a class="nav-link">Features</a>
                          </li>
                          <li class="nav-item">
                             <a class="nav-link">Pricing</a>
                          </li>
                          <li class="nav-item">
                             <a class="nav-link">About</a>
                          </li>
                          <li class="nav-item">
                             <a class="nav-link">Contact</a>
                          </li>
                       </ul>
                       <div class="login">
                          <ul>
                             <li><a href="#">Sign Up</a></li>
                             <li><a href="#">Register</a></li>
                          </ul>
                       </div>
                    </div>
                 </div>
              </nav>
           </div>
        </div>
     </div>
  </section>
</template>



<script setup></script>



<style scoped>
.header-area {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 999;
    background: #fff;
    width: 100%;
    padding: 10px 0;
    -webkit-box-shadow: 0 4px 15px -5px rgba(0, 0, 0, 0.1);
    box-shadow: 0 4px 15px -5px rgba(0, 0, 0, 0.1);
}
.navbar-brand {
    font-size: 24px;
    color: #000;
    font-weight: 700;
}

span.dot {
    color: #407BFF !important;
}
.navbar-expand-lg .navbar-nav .nav-link {
    font-size: 14px;
    padding: 10px 15px;
    display: inline-block;
    color: #000000;
}

.dropdown-menu {
    -webkit-box-shadow: 0 2px 10px -2px rgba(0, 0, 0, 0.1);
    box-shadow: 0 2px 10px -2px rgba(0, 0, 0, 0.1);
    padding: 20px 0;
    background: #ffffff;
    border: none;
}
.login li {
    display: inline-block;
    margin-left: 8px;
}
.login li a {
    padding: 5px 22px;
    border: 1px solid rgba(0, 0, 0, 0.1);
    color: #000000;
    border-radius: 30px;
}
.login li:last-child a {
    background: #407BFF;
    border: 1px solid #407BFF;
    color: #fff;
}

















</style>

