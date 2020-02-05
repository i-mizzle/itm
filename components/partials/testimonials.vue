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
                                <div class="col-lg-1 col-md-1 col-sm-1 col-xs-1 offset-lg-2 offset-md-2 offset-sm-2 offset-xs-2">
                                    <div class="twitter-bg">
                                        <i class="fab fa-twitter"></i>
                                    </div>
                                </div>
                                <div class="col-lg-7 col-md-7 col-sm-7 col-xs-7">
                                    <p>Had the privilege of sitting with <a href="https://twitter.com/ItmNigerialtd" target="_blank">@ItmNigerialtd</a>
 to conduct interviews for prospective employees. I must say they are thorough indeed, and it was a good experience</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-female.jpg"><strong>Geraldine Oba</strong></p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-1 col-md-1 col-sm-1 col-xs-1 offset-lg-2 offset-md-2 offset-sm-2 offset-xs-2">
                                    <div class="twitter-bg">
                                        <i class="fab fa-twitter"></i>
                                    </div>
                                </div>
                                <div class="col-lg-7 col-md-7 col-sm-7 col-xs-7">
                                    <p>Thank you so much <a href="https://twitter.com/ItmNigerialtd" target="_blank">@ItmNigeria</a> for career opportunities.</p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-female.jpg"><strong>Geraldine Oba</strong></p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-1 col-md-1 col-sm-1 col-xs-1 offset-lg-2 offset-md-2 offset-sm-2 offset-xs-2">
                                    <div class="twitter-bg">
                                        <i class="fab fa-twitter"></i>
                                    </div>
                                </div>
                                <div class="col-lg-7 col-md-7 col-sm-7 col-xs-7">
                                    <p>Thank you so much! You are the best!! Best recruitment team!! Best recruitment process!! </p>
                                    <p><img class="testifier-image" src="../../assets/img/generic-female.jpg"><strong>Juliet Eseogu</strong></p>
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

    .twitter-bg{
        background-color:#1CA0F0;
        height:150px;
        width:100%;
        display: flex;
        align-items: center;
        justify-content: center;
        color:#fff;
    }
    h5{
        color: #000;
        margin-bottom: 20px;
        font-family: 'Montserrat', sans-serif;
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
