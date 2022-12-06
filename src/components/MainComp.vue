<template>
    <div>
        <section id="table">
          <table>
            <tr>
                <th>A GLOBAL VIEW</th>
                <th>EXPERT LAWYERS</th>
                <th>CLIENT FOCUS</th>
                <th>LOCAL KNOWLEDGE</th>
            </tr>
            <tr>
                <td>Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</td>
                <td>Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</td>
                <td>Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</td>
                <td>Nullam fringilla tristique elit id varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</td>
            </tr>
          </table>
        </section>

        <section id="askex">
            <h1>QUESTIONS ABOUT A JUDICIAL ISSUE? ASK OUR EXPERTS.</h1>
            <button type="button">ASK AN EXPERT</button>
        </section>

        <section id="container">
            <h1>GLOBAL CHALLENGE. WORLD CLASS RESPONSE</h1>
            <div class="cards">
                <CardComp
                 v-for="(elem, index) in products"
                 :key="index" 
                 :dettagliCard="elem" />
            </div>
        </section>

        <section id="envato">
            <img src="../assets/img/envato-logo.png" alt="">
            <h4>"We have worked with Avada Low for the past 15 years. As we have grown and evolved, what I have valued most about our relationship is that Avada Low know us and our business."</h4>
            <h3>Nigel Rawlinson-Senior Partner</h3>
        </section>

        <section id="">
           <div>
        
           </div>
        </section>
    </div>
</template>

<script>
import CardComp from './CardComp.vue'
    export default {
        name: 'MainComp' ,
        components: {
            CardComp
        },
        data(){
            return{
                products: [
                    {
                        src: "../assets/img/column1-image1.jpg",
                        titolo: "Deborah Brown",
                    },
                    {
                        src: "../assets/img/column2-image1.jpg",
                        titolo: "Tax Litigation",
                    },
                    {
                        src: "../assets/img/column3-image1.jpg",
                        titolo: "Low Oil Prices",
                    },
                    {
                        src: "../assets/img/column1-image2.jpg",
                        titolo: "Allen Lucas",
                    },
                    {
                        src: "../assets/img/column2-image2.jpg",
                        titolo: "Aquisitions",
                    },
                    {
                        src: "../assets/img/column3-image2.jpg",
                        titolo: "Cost of Divorce",
                    },
                    {
                        src: "../assets/img/column1-image3.jpg",
                        titolo: "Muriel Potter",
                    },
                    {
                        src: "../assets/img/column2-image3.jpg",
                        titolo: "Financial Advice",
                    },
                    {
                        src: "../assets/img/column3-image3.jpg",
                        titolo: "2015 Tax Laws",
                    },
                    {
                        src: "../assets/img/column1-image4.jpg",
                        titolo: "Ken Douglas",
                    },
                    {
                        src: "../assets/img/column2-image4.jpg",
                        titolo: "International",
                    },
                    {
                        src: "../assets/img/column3-image4.jpg",
                        titolo: "Surveys Matter",
                    },
                    {
                        src: "../assets/img/column1-image5.jpg",
                        titolo: "Loretta Harris",
                    },
                    {
                        src: "../assets/img/column2-image5.jpg",
                        titolo: "Oil and Gas",
                    },
                    {
                        src: "../assets/img/column3-image5.jpg",
                        titolo: "In-House Work",
                    },
                    {
                        src: "../assets/img/column1-image6.jpg",
                        titolo: "Phill Russell",
                    },
                    {
                        src: "../assets/img/column2-image6.jpg",
                        titolo: "Capital Markets",
                    },
                    {
                        src: "../assets/img/column3-image6.jpg",
                        titolo: "Obama Care",
                    },

                ]
            }
        }
    }
</script>

<style lang="scss" scoped>

#table{

    table{
        padding: 80px;
    }

    th{
        padding: 10px;
    }

    td{
        text-align: center;
    }
}

#askex{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
    background-color: #54a096;
    color: white;

    button{
        padding: 10px;
        border: none;
        float: right;
        background-color: #74a59e;
        color: white;
    }
}

#container{
    width: 80%;
    margin: 0 auto;

    h1{
        padding: 100px;
        text-align: center;
    }
}

.cards{
    display: flex;
    flex-wrap: wrap;
    gap: 0.5%;
}

#envato{
    padding: 100px;
    margin-top: 50px;
    background-image: url(../assets/img/showeare-parallax.jpg);
    color: white;
    text-align: center;

    img{
        padding: 20px;
    }

    h4{
        text-align: left;
    }

    h3{
        text-align: center;
    }
}


</style>