<template>
    <section class="flex-display">
        <div>
            <div class="container">
                <div class="row">
                    <div class="col-md-8 ml-auto mr-auto text-center">
                        <!-- <h5>Have what it takes to join us?</h5> -->
                        <h5>Our E-Learning Platform</h5>
                        <p>Explore our e-learning platform and find courses tailored for you to learn at your own pace.</p>
                        <!-- <a href="https://qrgo.page.link/dqN5F">Upload Your CV</a> -->
                        <div class="video">
                            <div class="overlay">
                                <a data-toggle="modal" data-target="#exampleModalCenter">
                                    <i class="fas fa-play fa-3x" />
                                </a>
                            </div>
                            <!-- <img src="../../assets/img/elearning.jpg" alt="" class="post-image mb-3"> -->
                        </div>

                        <a href="https://nigeria.elearning.itmafrica.com/" target="_blank" class="button">JOIN IN</a>
                    </div>
                </div>
            </div>
        </div>

      <div
        id="exampleModalCenter"
        class="modal fade"
        tabindex="-1"
        role="dialog"
        aria-labelledby="exampleModalCenterTitle"
        aria-hidden="true"
      >
        <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
          <div class="modal-content">
            <div class="modal-header">
              <h6 id="exampleModalCenterTitle" class="modal-title">
                Video Title
              </h6>
              <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
              </button>
            </div>
            <div class="modal-body" style="height: 500px">
              <iframe width="100%" height="100%" src="https://www.youtube.com/embed/DxsgaL5RTUg?start=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
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
    section.flex-display{
        background-color: #284a98;
        justify-content: center;
        min-height:5vh;
        height:inherit;
        padding:50px;
    }

    h5{
        color: #ffffffda;
        margin-bottom: 10px;
    }

    p{
        color:#ffffffd3;
    }

    .video{
        position: relative;
    }

    a.button{
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
    a.button:hover{
        background-color:#15556d;
        color: #fff;
    }

    img{
        width: 100%;
        border-radius: 10px;
        border: 5px solid #3FBEEB;
    }

    .video{
        width: 100%;
        border-radius: 10px;
        border: 5px solid #3FBEEB;
        background: url('../../assets/img/elearning.jpg') no-repeat center center;
        background-size:cover;
        height: 300px;
    }
    .video .overlay {
  width:100%;
  position:absolute;
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#000000+0,000000+100 */
  background: #000000c4; /* Old browsers */
  background: -moz-linear-gradient(top, #000000c4 0%, #00000000 90%); /* FF3.6-15 */
  background: -webkit-linear-gradient(top, #000000c4 0%,#00000000 90%); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #000000c4 0%,#00000000 90%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#000000c4', endColorstr='#00000000',GradientType=0 ); /* IE6-9 */
  display: flex;
  align-items: center;
  justify-content: center;
  height: 300px;
  /* padding: 180px; */
  z-index: 98;
  transition: all 500ms ease;
  cursor: pointer;
  border-radius: 10px;
  /* border-top-right-radius: 10px; */
}

.video .overlay:hover {
  background: #000000c4; /* Old browsers */
  background: -moz-linear-gradient(top, #000000ea 0%, #00000000 90%); /* FF3.6-15 */
  background: -webkit-linear-gradient(top, #000000ea 0%,#00000000 90%); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #000000ea 0%,#00000000 90%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#000000ea', endColorstr='#00000000',GradientType=0 ); /* IE6-9 */
}

.overlay i {
  color:#fff;
}

</style>
