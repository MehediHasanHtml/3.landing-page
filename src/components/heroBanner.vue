<template>
    <section class="hero-banner">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <div class="hero-title">
                        <h1>{{ title }}</h1>
                        <p>{{ subtitle }}</p>
                        <div class="btns">
                            <ul>
                                <li><a href="#">See Features</a></li>
                                <li><a href="#">Pricing</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="hero-img">
                        <img class="img-fluid" src="../assets/img/market-launch-pana.svg" alt="market-launch-pana">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script setup>


const title = 'Promote Your Products by Colorlib'
const subtitle = 'Another cool free html css template by Colorlib Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast.';

</script>

<style scoped>
.hero-banner {
    margin-top: 82px;
    padding: 50px 0;
}

.hero-title h1 {
    font-size: 70px;
    line-height: 1;
    font-weight: 700;
    color: #000000;
    margin-bottom: 30px;
}
.hero-title p {
    font-size: 16px;
    color: #939393;
    line-height: 1.5;
    margin-bottom: 30px;
}

.btns li {
    display: inline-block;
    margin-right: 8px;
}
.btns li a {
    color: #fff;
    background-color: #0062cc;
    border: 1px solid #005cbf;
    border-radius: 30px;
    font-size: 11px;
    text-transform: uppercase;
    font-weight: 700;
    letter-spacing: .05rem;
    padding: 15px 30px;
    transition: all 0.3s ease;
}
.btns li:last-child a {
    color: #005cbf;
    background-color: #fff;
    border: 1px solid #005cbf;
}
.btns li a:hover {
    color: #fff;
    background-color: #0062cc;
    border: 1px solid #005cbf;
    transition: all 0.3s ease;
}

.hero-img {
    position: relative;
    z-index: 1;
}

.hero-img img {
    width: 100%;
}

.hero-img::after {
    display: block;
    content: '';
    clear: both;
    background: url(../assets/img/dots.png.webp);
    background-repeat: no-repeat;
    background-size: cover;
    position: absolute;
    top: 0;
    right: -33%;
    z-index: -1;
    height: 300px;
    width: 300px;
}

@media (max-width: 1199.98px) {
    .hero-img::after{
        display: none;
    }
    .hero-title h1 {
        font-size: 40px;
    }
}

@media (max-width: 991.98px) {
    .hero-title {
        margin-bottom: 30px;
    }
}



</style>