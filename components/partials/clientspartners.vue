<template>
    <section class="half">
        <div>
            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-12">
                        <h5>CLIENTS & PARTNERS</h5>
                        <div class="underline"></div>
                    </div>
                    <!-- <div class="col-lg-2 col-md-6 text-center" style="padding-top:40px;">
                        <img class="client" src="../../assets/img/client1.png">
                    </div>
                    <div class="col-lg-2 col-md-6 text-center">
                        <img class="client" src="../../assets/img/client2.jpg">
                    </div>
                    <div class="col-lg-2 col-md-6 text-center">
                        <img class="client" src="../../assets/img/client3.jpg">
                    </div>
                    <div class="col-lg-2 col-md-6 text-center">
                        <img class="client" src="../../assets/img/client4.jpg">
                    </div> -->
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/client-npf.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3  text-center">
                        <img class="client" src="../../assets/img/client-fcta.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3  text-center">
                        <img class="cliet" src="../../assets/img/client-c1.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3  text-center">
                        <img class="client" src="../../assets/img/client-c.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/client-agt.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/partner-istrom.jpg">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/partner-taj.jpeg">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/partner-kingfem.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/partner-1.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/partner-2.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center mt-5">
                        <img class="client mt-5" src="../../assets/img/ngf.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center bg-black">
                        <img class="client" src="../../assets/img/samubil.png">
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-3 text-center">
                        <img class="client" src="../../assets/img/steelbridge.png">
                    </div>
                </div>
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
        font-family: 'Montserrat', sans-serif;
        font-weight: 700;
    }

    p{
        color:#ffffffd3;
    }

    a{
        color: #1e1d1d;
        background-color:#3FBEEB;
        font-size:0.8em;
        border:none;
        padding:15px;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Montserrat', sans-serif;
        border-radius: 3px;
        display: inline-block;
        margin-top: 20px;
        text-decoration: none;
    }
    a:hover{
        background-color:#15556d;
        color: #fff;
    }

    img.client{
        width:100%;
        margin-top:30px;
    }

    .bg-black{
        background-color:black;
    }

    @media screen and (max-width: 768px) {
        section{
            background-color: #fff;
            padding:30px;
        }
        img.client{
            width:80%;
        }
    }

</style>
