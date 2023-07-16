<template>
    <section class="dashboard">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <div class="dash-img">
                        <img class="img-fluid" src="../assets/img/dashboard.jpg.webp" alt="dashboard">
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="dash-con">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <i class="bi bi-app-indicator bg-info"></i>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Grow Your Business</h4>
                                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <i class="bi bi-arrow-repeat bg-warning"></i>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Build Products</h4>
                                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <i class="bi bi-envelope bg-danger"></i>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Success Every Day</h4>
                                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <i class="bi bi-collection bg-primary"></i>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h4>Bring Ideas to Life</h4>
                                <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.</p>
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
.dashboard {
    background-color: #f8f9fa;
    padding: 80px 0;
}
.dash-img img {
    width: 100%;
}

.dash-con .d-flex{
    padding: 15px;
    margin-bottom: 30px;

}

.dash-con .d-flex i{
    padding: 6px 10px;
    font-size: 24px;
    border-radius: 10px;
    color: #fff;
    -webkit-box-shadow: 0 2px 10px 0 rgba(255, 201, 60, 0.3);
    box-shadow: 0 2px 10px 0 rgba(255, 201, 60, 0.3);
}
.dash-con .d-flex h4 {
    font-size: 18px;
    font-weight: 500;
    line-height: 1.2;
    color: #000;
    margin-bottom: 10px;
}

.dash-con .d-flex p {
    font-size: 16px;
    line-height: 1.5;
    color: #939393;
}


@media (max-width: 991.98px) {
    .dash-img {
        margin-bottom: 30px;
    }
}


</style>