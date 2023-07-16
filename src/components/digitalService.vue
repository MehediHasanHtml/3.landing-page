<template>
    <section class="digital-services">
        <div class="container">
            <div class="row">
                <div class="col-lg-5">
                    <div class="title">
                        <h4>{{ suntitle }}</h4>
                        <h2>{{ title }}</h2>
                    </div>
                    <div class="content">
                        <p>{{ cosntent }}</p>
                        <ul>
                            <li><i class="bi bi-check2"></i> There live the blind texts </li>
                            <li><i class="bi bi-check2"></i> Far far away behind the word</li>
                        </ul>
                        <p> <i>{{ content2 }}</i></p>

                        <div class="man d-flex align-items-center">
                            <div class="flex-shrink-0">
                                <img class="img-fluid" src="../assets/img/person_1.jpg.webp" alt="man">
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>James Anderson</h4>
                                <p>Facebook, Product Lead</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-7">
                    <div class="videos">
                        <img class="img-fluid" src="../assets/img/dashboard.jpg.webp" alt="dashboard">
                        <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal"><i class="bi bi-play-circle"></i> </a>
                    </div>
                </div>
            </div>
        </div>
    </section>



<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-xl">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div class="ratio ratio-16x9">
            <iframe src="https://www.youtube.com/embed/xcJtL7QggTI" title="YouTube video" allowfullscreen></iframe>
        </div>
    
      </div>
    </div>
  </div>
</div>
</template>

<script setup>
const title = 'Selling Digital Services'
const suntitle = 'DIGITAL SERVICES'
const cosntent = 'Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast.'
const content2 = '“Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. ”';

</script>

<style>
.digital-services {
    padding: 100px 0;
}

.content p {
    line-height: 1.5;
    font-size: 16px;
    color: #939393;
    margin-bottom: 15px;
}

.content p i {
    font-style: italic;
}

.content li {
    line-height: 1.5;
    font-size: 16px;
    color: #939393;
    margin-bottom: 15px;
}

.content li i {
    color: #407BFF;
}

.man img {
    height: 50px;
    border-radius: 50%;
}

.man h4 {
    font-weight: 400;
    color: #000000;
    font-size: 14px;
}
.man p {
    font-weight: 400;
    color: #999;
    font-size: 14px;
}

.videos img {
    width: 100%;
}
.videos {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
    z-index: 1;
} 
.videos:hover:after  {
    transition: all 0.3s ease;
    background: rgba(0, 0, 0, 0.1);
}

.videos:after {
    display: block;
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    -webkit-transition: .3s all ease;
    -o-transition: .3s all ease;
    transition: .3s all ease;
    z-index: 1;
}


.videos a {
    display: block;
    font-size: 32px;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    padding: 10px;
    color: #999;
    background: #fff;
    -webkit-box-shadow: 0 15px 30px 0 rgba(0, 0, 0, 0.5);
    box-shadow: 0 15px 30px 0 rgba(0, 0, 0, 0.5);
    line-height: 32px;
    position: absolute;
    margin: 0 auto;
    text-align: center;
    z-index: 999;
}


@media (max-width: 991.98px) {
    .content {
        margin-bottom: 30px;
    }
}


</style>