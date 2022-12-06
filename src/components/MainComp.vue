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

        <section id="cards">
            <h1>GLOBAL CHALLENGE. WORLD CLASS RESPONSE</h1>
            <CardComp/>
        </section>

        <section id="envato">
            <img src="../assets/img/envato-logo.png" alt="">
            <h4>"We have worked with Avada Low for the past 15 years. As we have grown and evolved, what I have valued most about our relationship is that Avada Low know us and our business."</h4>
            <h3>Nigel Rawlinson-Senior Partner</h3>
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

#cards{
    h1{
        padding: 100px;
        text-align: center;
    }
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