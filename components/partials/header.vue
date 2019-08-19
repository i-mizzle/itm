<template>
<header>
    <div class="container-fluid">
        <div class="row top-row">
            <div class="col-md-6">
                <p>
                    <i class="fas fa-envelope"></i><span class="email">info.abuja@itmafrica.com</span><br>
                    <i class="fas fa-phone"></i><span class="phone">(+234) 702 509 0000</span><br>
                    <!-- <img src="../../assets/img/phone.png"><span class="phone">(+234) 702 509 0000</span><br> -->
                    <!-- <img src="../../assets/img/mail.png"><span class="email">info.abuja@gmail.com</span><br> -->
                    <a href="https://web.facebook.com/ITMNigeriaLtd/" target="_blank"><i class="fab fa-facebook-f fa-lg"></i></a> 
                    <a href="https://twitter.com/ItmNigerialtd" target="_blank"><i class="fab fa-twitter fa-lg"></i></a> 
                    <a href="https://www.linkedin.com/in/itm-nigeria-limited-002497183/" target="_blank"><i class="fab fa-linkedin fa-lg"></i></a>

                </p>
            </div>
            <div class="col-md-6">
                <ul class="flags">
                    <li class="country tanzania">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                    <li class="country congo">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                    <li class="country rwanda">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                    <li class="country angola">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                    <li class="country allemagne">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                    <li class="country burundi">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                    <li class="country southafrica">
                        <a href="https://itmafrica.com" target="_blank"></a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12">
                <nav class="navbar navbar-expand-lg">
                    <a class="navbar-brand" href="#">
                        <img class="logo" src="../../assets/img/logo-nigeria.png" alt="ITM Nigeria">
                    </a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                        <!-- <span class="navbar-toggler-icon"></span> -->
                        <img src="../../assets/img/menu.svg">
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav ml-auto">
                            <!-- <a class="nav-item nav-link" href="#">About Us</a> -->
                            <nuxt-link class="nav-item nav-link" :to="{ path: '/',hash:'#about'}">About Us</nuxt-link>
                            <!-- <a class="nav-item nav-link" href="#">Our Services</a> -->
                            <nuxt-link class="nav-item nav-link" :to="{ path: '/',hash:'#services'}">Our Services</nuxt-link>
                            <!-- <a class="nav-item nav-link" href="#">Clients & Partners</a> -->
                            <nuxt-link class="nav-item nav-link" :to="{ path: '/',hash:'#clients'}">Clients & Partners</nuxt-link>
                            <!-- <a class="nav-item nav-link" href="#">Testimonials</a> -->
                            <nuxt-link class="nav-item nav-link" :to="{ path: '/',hash:'#testimonials'}">Testimonials</nuxt-link>
                            <!-- <a class="nav-item nav-link" href="#">Get in Touch</a> -->
                            <nuxt-link class="nav-item nav-link" :to="{ path: '/',hash:'#contact'}">Get in Touch</nuxt-link>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</header>
</template>

<script>

export default {
  components: {
  },
  data(){
      return {}
  }
}
</script>

<style scoped>
    header{
        position:relative;
        top: 20px;
        left:0;
        width:100%;
        z-index:999;
        padding-left:5%;
        padding-right:5%;
    }
    nav{
        padding:15px 30px;
        background-color: #284A98;
    }
    a i{
        color:#1b1a1a;
    }
    a i:hover{
        color:#575555;
    }
    i.fab{
        margin-right:20px;
        margin-top:10px;
    }
    a.navbar-brand{
        width:8%;
        margin-left:20px;
    }

    ul.flags{
        list-style: none;
        float:right;
    }

    li.country{
        width:40px;
        height:40px;
        border-radius:50%;
        margin-bottom:10px;
        float: right;
        margin-left:10px;
        cursor:pointer;
        margin-top:20px;
    }

    li.country.tanzania{
        background: url('../../assets/img/tz.png') no-repeat center center;
        background-size: cover;
    }
    li.country.allemagne{
        background: url('../../assets/img/de.png') no-repeat center center;
        background-size: cover;
    }
    li.country.burundi{
        background: url('../../assets/img/bi.png') no-repeat center center;
        background-size: cover;
    }
    li.country.congo{
        background: url('../../assets/img/cd.png') no-repeat center center;
        background-size: cover;
    }
    li.country.rwanda{
        background: url('../../assets/img/rw.png') no-repeat center center;
        background-size: cover;
    }
    li.country.angola{
        background: url('../../assets/img/ao.png') no-repeat center center;
        background-size: cover;
    }
    li.country.southafrica{
        background: url('../../assets/img/sa.png') no-repeat center center;
        background-size: cover;
    }

    img.logo{
        width:100%;
    }

    a.nav-link{
        color:#fff;
        font-size: 1em;
        font-family: 'Poppins', sans-serif;
    }

    span.phone, span.email {
        margin-left: 10px;
        margin-right:10px;
        color:#1b1a1a;
    }

    button.navbar-toggler-icon{
        color:#fff;
        z-index: 999;
    }

    @media screen and (max-width: 768px) {
        .top-row{
            display:none;
        }
        header{
            position:absolute;
            top: 0;
            left:0;
            width:100%;
            z-index:999;
            padding-left:1%;
            padding-right:1%;
            background: #fff;
        }
         img.logo{
            width:300%;
            max-width: unset;
        }
        nav{
            background-color:transparent;
        }
        .navbar-nav{
            padding:15px 30px;
            background-color: #284A98;
        }

    }
</style>
