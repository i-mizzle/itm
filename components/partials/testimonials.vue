<template>
    <section class="half">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <h5>TESTIMONIALS</h5>
                    <div class="underline"></div>
                </div>
            </div>
        </div>
        <div class="bd-example">
            <div id="testimonialsCarousel" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#testimonialsCarousel" data-slide-to="0" class="active"></li>
                    <li data-target="#testimonialsCarousel" data-slide-to="1"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-6 col-md-6 offset-lg-3 offset-md-3">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-female.jpg"><strong>Donec Pede J.</strong></p>
                                </div>
                                <!-- <div class="col-lg-4 col-md-6">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/profile1.jpeg"><strong>Donec Pede J.</strong></p>
                                </div>
                                <div class="col-lg-4 col-md-6">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/profile2.jpeg"><strong>Donec Pede J.</strong></p>
                                </div> -->
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="container">
                            <div class="row">
                                <!-- <div class="col-lg-4 col-md-6">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-female.jpg"><strong>Donec Pede J.</strong></p>
                                </div> -->
                                <div class="col-lg-6 col-md-6 offset-lg-3 offset-md-3">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-male.jpeg"><strong>Donec Pede J.</strong></p>
                                </div>
                                <!-- <div class="col-lg-4 col-md-6">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/profile3.jpeg"><strong>Donec Pede J.</strong></p>
                                </div> -->
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="container">
                            <div class="row">
                                <!-- <div class="col-lg-4 col-md-6">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-female.jpg"><strong>Donec Pede J.</strong></p>
                                </div> -->
                                <!-- <div class="col-lg-4 col-md-6">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-male.jpeg"><strong>Donec Pede J.</strong></p>
                                </div> -->
                                <div class="col-lg-6 col-md-6 offset-lg-3 offset-md-3">
                                    <p>In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium.</p>
                                    <p><img class="testifier-image" src="../../assets/img/profile3.jpeg"><strong>Donec Pede J.</strong></p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <a class="carousel-control-prev" href="#testimonialsCarousel" role="button" data-slide="prev">
                <!-- <span class="carousel-control-prev-icon" aria-hidden="true"></span> -->
                <img class="slider-control" src="../../assets/img/angle-left.svg">
                <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#testimonialsCarousel" role="button" data-slide="next">
                <!-- <span class="carousel-control-next-icon" aria-hidden="true"></span> -->
                <img class="slider-control" src="../../assets/img/angle-right.svg">
                <span class="sr-only">Next</span>
                </a>
            </div>
            </div>
    </section>
</template>

<script>

export default {
  components: {
  },
}
</script>

<style scoped>
    section{
        background-color: #fff;
        padding:100px;
    }

    h5{
        color: #000;
        margin-bottom: 20px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    p{
        color:#000;
    }

    img.testifier-image{
        width:50px;
        height:50px;
        border-radius: 50%;
        border: 2px solid #38B0E6;
        margin-right: 10px;
    }

    @media screen and (max-width: 768px) {
        section{
            padding:30px;
        }
    }

</style>
