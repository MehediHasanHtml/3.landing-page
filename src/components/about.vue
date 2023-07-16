<template>
    <section class="about-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-7">
                    <div class="about-img">
                        <img class="img-fluid" src="../assets/img/about.svg" alt="">
                    </div>
                </div>
                <div class="col-lg-5">
                    <div class="about-con">
                        <div class="title">
                            <h4>{{ subtitle }}</h4>
                            <h2>{{ title }}</h2>
                        </div>
                        <p>{{content}}</p>

                        <ul>
                            <li><i class="bi bi-check2"></i> There live the blind texts</li>
                            <li><i class="bi bi-check2"></i> Far far away behind the word</li>
                            <li><i class="bi bi-check2"></i> Their place and supplies</li>
                        </ul>

                        <div class="member row">
                            <div class="col">
                                <h2>59M</h2>
                                <p>MEMBERS</p>
                            </div>
                            <div class="col">
                                <h2>14</h2>
                                <p>TEAM</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script setup>
const title = 'About Us'
const subtitle = 'ABOUT'
const content = 'Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia.';

</script>


<style scoped>
.about-area {
    padding: 50px 0;
}
.about-img img {
    width: 100%;
}

.about-con p {
    line-height: 1.5;
    font-size: 16px;
    color: #939393;
    margin-bottom: 15px;
}

.about-con li {
    line-height: 1.5;
    font-size: 16px;
    color: #939393;
    margin-bottom: 15px;
}

.about-con li i {
    color: #407BFF;
}

.member h2 {
    color: #000000;
    font-size: 40px;
}
.member p {
    text-transform: uppercase;
    font-size: 11px;
    font-weight: 700;
    letter-spacing: .1rem;
}

@media (max-width: 991.98px) {
    .about-img {
        margin-bottom: 30px;
    }

}


</style>