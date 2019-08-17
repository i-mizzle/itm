<template>
    <footer>
        <section class="half">
            <div class="container">
                <div class="row">
                    <div class="col-lg-3 col-md-4 col-xs-12">
                        <h5>Scan to Upload Your CV</h5>
                        <img class="qrcode" src="../../assets/img/qrcode.png" alt="Scan this to apply">
                    </div>
                    <div class="col-lg-4 col-md-4 col-xs-12">
                        <h5>Contact Us</h5>
                        <form>
                            <input type="text" placeholder="your name" required>
                            <input type="email" placeholder="your email address" required>
                            <textarea placeholder="your message"></textarea>
                            <button type="submit"> Send a message </button>
                        </form>

                    </div>
                    <div class="col-lg-3 col-md-4 col-xs-12">
                        <h5>Find Us Here</h5>
                        <div class="contact-block">
                            <img src="../../assets/img/location.png">
                            <p>No 47, Kumasi Crescent Wuse 2, Abuja<br>Nigeria</p>
                        </div>
                        <div class="contact-block">
                            <img src="../../assets/img/mail.png">
                            <p>info.abuja@itmafrica.com</p>
                        </div>
                        <div class="contact-block">
                            <img src="../../assets/img/phone.png">
                            <p>(+234) 702 509 0000</p>
                        </div>

                        <ul class="socials">
                            <li>
                                <a href="https://web.facebook.com/ITMNigeriaLtd/" target="_blank"><img src="../../assets/img/fb.png"></a>
                            </li>
                            <li>
                                <a href="https://twitter.com/ItmNigerialtd" target="_blank"><img src="../../assets/img/tw.png"></a>
                            </li>
                            <li>
                                <a href="https://www.linkedin.com/in/itm-nigeria-limited-002497183/" target="_blank"><img src="../../assets/img/in.png"></a>
                            </li>
                        </ul>
                        
                    </div>
                </div>
            </div>
        </section>
    </footer>
</template>

<script>

export default {
  components: {
  },
}
</script>

<style scoped>
    section{
        background: url('../../assets/img/map.png') no-repeat center right;
        background-size:30%;
    }

    footer{
        padding:100px;
        background-color: #1a1919;
    }

    .contact-block{
        padding-bottom:20px;
        clear: both;
        position: relative;
        overflow: hidden;
    }

    .contact-block img{
        float: left;
        margin-right: 10px;
        margin-bottom:10px;
    }

    .contact-block p{
        color:#ffffffb4;
        width: 85%;
        float: right;
    }

    h5{
        color: #ffffffda;
        margin-bottom: 20px;
    }

    ul.socials{
        list-style: none;
        margin-left:0;
    }

    ul.socials li {
        float:left;
        margin-left:0;
        margin-right:10px;
    }

    ul.socials li a img{
        width:40px;
    }

    input[type=text], input[type=email], textarea{
        background-color: #1e1d1d;
        color:#ffffffe3;
        font-size:0.8em;
        border:none;
        padding:15px;
        width:100%;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Poppins', sans-serif;
    }

    input[type=text]:focus, input[type=email]:focus, textarea:focus{
        background-color: #363636;
    }

    button{
        color: #1e1d1d;
        background-color:#3FBEEB;
        font-size:0.8em;
        border:none;
        padding:15px;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Poppins', sans-serif;
    }
    button:hover{
        background-color:#15556d;
        color: #fff;
    }

    textarea{
        height:100px;
        resize:none;
    }

    img.qrcode{
        margin-top:45px;
        width:100%;
    }

    @media screen and (max-width: 1024px) {
        section{
            background-size:50%;
        }

        .contact-block p{
            font-size:0.8em;
        }

        ul.socials li a img{
            width:20px;
        }
    }

    @media screen and (max-width: 768px) {
        section{
            background: url('../../assets/img/map.png') no-repeat bottom right;
        }
        footer{
            padding:30px;
            background-color: #1a1919;
        }
        h5{
            margin-bottom: 20px;
            margin-top: 20px;
        }

    }

@media screen and (max-width: 425px) {
    img.qrcode{
        width:100%;
    }
}

</style>
