<template>
    <section class="flex-display">
        <div>
            <div class="container">
                <div class="row">
                    <div class="col-md-12 text-center">
                        <!-- <h5>Have what it takes to join us?</h5> -->
                        <h5>Add your CV to our talent pool</h5>
                        <a href="https://qrgo.page.link/dqN5F">Upload your CV</a>
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

    a{
        color: #1e1d1d;
        background-color:#3FBEEB;
        font-size:0.8em;
        border:none;
        padding:15px;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Poppins', sans-serif;
        border-radius: 3px;
        display: inline-block;
        margin-top: 20px;
        text-decoration: none;
    }
    a:hover{
        background-color:#15556d;
        color: #fff;
    }

</style>
