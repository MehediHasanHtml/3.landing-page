<template>
    <section class="news-area">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="title text-center">
                        <h2>Our News</h2>
                        <p>Far from the countries Vokalia and Consonantia</p>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="news">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                               <img class="img-fluid" src="../assets/img/person_2.jpg.webp" alt="">
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Posted by James</h4>
                                <p>Jun 14, 2020</p>
                            </div>
                        </div>
                        <p>Digital Service, 4 min read</p>
                        <a href="#">Far far away behind the word mountains far from the countries</a>

                        <i class="bi bi-arrow-right"></i>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="news">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                               <img class="img-fluid" src="../assets/img/person_2.jpg.webp" alt="">
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Posted by James</h4>
                                <p>Jun 14, 2020</p>
                            </div>
                        </div>
                        <p>Digital Service, 4 min read</p>
                        <a href="#">Far far away behind the word mountains far from the countries</a>

                        <i class="bi bi-arrow-right"></i>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="news">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                               <img class="img-fluid" src="../assets/img/person_2.jpg.webp" alt="">
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Posted by James</h4>
                                <p>Jun 14, 2020</p>
                            </div>
                        </div>
                        <p>Digital Service, 4 min read</p>
                        <a href="#">Far far away behind the word mountains far from the countries</a>

                        <i class="bi bi-arrow-right"></i>
                    </div>
                </div>


            </div>
        </div>
    </section>
</template>


<script setup>

</script>


<style>
.news-area {
    padding: 100px 0;
    background-color: #f8f9fa;
}

.news {
    background: #ffffff;
    padding: 30px;
    position: relative;
    top: 0;
    -webkit-transition: .2s all ease;
    -o-transition: .2s all ease;
    transition: .2s all ease;;
    margin-bottom: 30px;
}
.news:hover {
    top: -10px;
    -webkit-box-shadow: 0 15px 30px 0 rgba(0, 0, 0, 0.05);
    box-shadow: 0 15px 30px 0 rgba(0, 0, 0, 0.05);
    -webkit-transition: .2s all ease;
    -o-transition: .2s all ease;
    transition: .2s all ease;;
}

.news img{
    height: 50px;
    border-radius: 50%;
}

.news h4 {
    font-size: 16px;
    font-weight: 400;
    display: block;
    font-weight: 700;
    color: #000000;
}

.news .d-flex  p {
    color: #c6c6c6;
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 0;
}

.news p {
    color: #c6c6c6;
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 15px;
}

.news .d-flex {
    margin-bottom: 15px;
}

.news a {
    display: block;
    font-size: 25px;
    line-height: 1.2;
    color: #000;
    margin-bottom: 15px;
}

.news i {
    font-size: 24px;
    line-height: 1.2;
}




</style>