<template>
    <section class="contact-area">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="title text-center">
                        <h2>Get In Touch</h2>
                        <p>Far from the countries Vokalia and Consonantia</p>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="contact-from">
                        <form action="">
                            <div class="row g-3">
                                <div class="col-md-6">
                                    <div class="form-floating">
                                        <input type="text" class="form-control" id="First" placeholder="First name">
                                        <label for="First">First name</label>
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <div class="form-floating">
                                        <input type="text" class="form-control" id="last" placeholder="Last name">
                                        <label for="last">last name</label>
                                    </div>
                                </div>
                                <div class="col-md-12">
                                    <div class="form-floating">
                                        <input type="email" class="form-control" id="Email" placeholder="Email address">
                                        <label for="Email">Email address</label>
                                    </div>
                                </div>
                                <div class="col-md-12">
                                    <div class="form-floating">
                                        <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
                                        <label for="floatingTextarea2">Comments</label>
                                    </div>
                                </div>
                                <div class="col-12">
                                    <button type="submit" class="btns">Send Message</button>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
                <div class="col-lg-1"></div>
                <div class="col-lg-5">
                    <div class="contact-info">
                        <h3>Contact Info</h3>
                        <p><i class="bi bi-geo-alt"></i> 43 Raymouth Rd. Baltemoer, London 3910</p>
                        <p><i class="bi bi-telephone"></i> +1(123)-456-7890</p>
                        <p><i class="bi bi-envelope"></i> info@mydomain.com</p>
                        <p><i class="bi bi-globe-americas"></i> https://Colorlib.com/</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>

</script>


<style scoped>
.contact-area {
    padding: 100px 0;
}

.form-control {
    display: block;
    width: 100%;
    padding: 0.375rem 0;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: var(--bs-body-color);
    background-color: var(--bs-body-bg);
    background-clip: padding-box;
    border: none;
    border-bottom: 1px solid #222;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border-radius: 0;
    transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
}

.form-control:focus {
    outline: 0;
    box-shadow: inherit;
}
.form-floating>.form-control, .form-floating>.form-control-plaintext {
    padding: 1rem 0;
}


.form-floating>label {
    padding: 1rem 0;
}
.btns {
    border: none;
    color: #fff;
    background-color: #407BFF;
    border: 1px solid #407BFF;
    border-radius: 30px;
    font-size: 11px;
    text-transform: uppercase;
    font-weight: 700;
    letter-spacing: .05rem;
    padding: 15px 30px;
    transition: all 0.3s ease;
}

.contact-info h3 {
    color: #000;
    line-height: 1.5;
    font-size: 22px;
    margin-bottom: 15px;
}
.contact-info p {
    color: #000;
    line-height: 1.5;
    font-size: 16px;
    margin-bottom: 15px;
}

.contact-info p i {
    color: #000;
    margin-right: 5px;
}

@media (max-width: 991.98px) {
    .contact-from {
        margin-bottom: 30px;
    }

}

</style>