<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <h5>OUR TEAM</h5>
                    <div class="underline"></div>
                </div>
            </div>

            <div class="row">
                <div class="col-md-4 mb-5">
                    <img src="../../assets/img/team-habibah.jpg">
                    <p class="name mt-3">Habibah</p>
                    <p class="bio">The main objective of my role is to ensure the Country office grows, in all facets. This also included creating & developing a business model from a concept note, conducting research & development of the market for ITM’s share, recruiting a young team, as well as strategically thriving in the organized private sector</p>
                </div>

                <div class="col-md-4 mb-5">
                    <img src="../../assets/img/team-tresor.jpg">
                    <p class="name mt-3">Tresor</p>
                    <p class="bio">As the Operation Manager and Under the supervision of the Country Manager, the main mission of this position is to ensure the control and approval of all operations for the growth of the business in the country, in accordance with the objectives assigned to the Country Manager</p>
                </div>
                
                <div class="col-md-4 mb-5">
                    <img src="../../assets/img/team-nafisah.png">
                    <p class="name mt-3">Nafisah</p>
                    <p class="bio">As the sales and Business Development Manager, my main goal is to develop strategic sales plan and strategies that will improve the market position and grow the profit of the company through attracting new customers and also increasing the revenue generated from existing customers.</p>
                </div>

                <div class="col-md-4 mb-5 ml-auto">
                    <img src="../../assets/img/team-evelyn.jpg">
                    <p class="name mt-3">Evelyn</p>
                    <p class="bio">As an Outsource Executive my primary responsibility is to supervise and control the performance of outsource staff. As a supervisor I liaison between ITM and the client company. Get feedbacks, complaint and suggestions from the client company and relaying them back to the Country Manager for directives.</p>
                </div>
                <div class="col-md-4 mb-5 mr-auto">
                    <img src="../../assets/img/team-victory.jpg">
                    <p class="name mt-3">Victory</p>
                    <p class="bio">The main objective of an accountant can be rounded up in this three activities Financing, Operations and Investing but it is not limited to these. An accountant also does budgeting, preparation, analysis and reporting of the financials of the company. </p>
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

    p.name {
        font-weight: 700;
        font-size: 1em;
        color: #215168;
    }

    p.bio{
        font-size: 0.8em;
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
