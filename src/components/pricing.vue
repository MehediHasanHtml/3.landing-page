<template>
    <section class="pricing-area">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="title text-center">
                        <h2>Pricing</h2>
                        <p>Pricing for everyone. Choose your plan now!</p>
                    </div>
                </div>
                <div class="col-lg-10 offset-lg-1">
                    <div class="row">
                        <div class="col-md-4">
                            <div class="pricing">
                                <h3>Free</h3>
                                <h4><sup>$</sup>0</h4>
                                <p><i class="bi bi-check2"></i> There live the blind texts</p>
                                <p><i class="bi bi-check2"></i> Far far away behind the word</p>
                                <p><i class="bi bi-check2"></i> Far from the countries Vokalia and Consonantia</p>
                                <a href="#">Get Started</a>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="pricing">
                                <h3>Standard</h3>
                                <h4><sup>$</sup>19.99</h4>
                                <p><i class="bi bi-check2"></i> There live the blind texts</p>
                                <p><i class="bi bi-check2"></i> Far far away behind the word</p>
                                <p><i class="bi bi-check2"></i> Far from the countries Vokalia and Consonantia</p>
                                <a href="#">Get Started</a>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="pricing">
                                <h3>Premium</h3>
                                <h4><sup>$</sup>79.99</h4>
                                <p><i class="bi bi-check2"></i> There live the blind texts</p>
                                <p><i class="bi bi-check2"></i> Far far away behind the word</p>
                                <p><i class="bi bi-check2"></i> Far from the countries Vokalia and Consonantia</p>
                                <a href="#">Get Started</a>
                            </div>
                        </div>
                    </div>
                </div>


            </div>
        </div>
    </section>
</template>


<script setup>

</script>


<style scoped>
.pricing-area {
    padding: 100px 0;
    background-color: #f8f9fa;
}
.pricing {
    background: #ffffff;
    border-radius: 40px;
    padding: 50px;
}

.pricing h3 {
    font-size: 30px;
    color: #000000;
    text-align: center;
}

.pricing h4 {
    color: #407BFF;
    font-size: 40px;
    text-align: center;
    margin-bottom: 15px;
}
.pricing h4 sup {
    font-size: 16px;
    top: -15px;
    margin-right: 5px;
}

.pricing p {
    position: relative;
    padding-left: 30px;
    margin-bottom: 15px;
    font-size: 16px;
    color: #939393;
}
.pricing p i {
    position: absolute;
    top: 0;
    left: 0;
    color: #407BFF;
}

.pricing a {
    display: block;
    margin: 0 auto;
    color: #0062cc;
    background-color: #fff;
    border: 1px solid #0062cc;
    border-radius: 30px;
    font-size: 11px;
    text-transform: uppercase;
    font-weight: 700;
    letter-spacing: .05rem;
    padding: 15px 30px;
    transition: all 0.3s ease;
    text-align: center;
    margin-top: 50px;
}

.pricing a:hover {
    color: #fff;
    background-color: #0062cc;
    border: 1px solid #0062cc;
    transition: all 0.3s ease;
}



@media (max-width: 991.98px) {
    .pricing {
        padding: 20px;
        margin-bottom: 30px;
    }

}


</style>