<template>
    <div>
            <section class="columns">
            <ColumnComp
            v-for="(elem, index) in products"
            :key="index" 
            :dettagliColumn="elem" />
        </section>

        <section id="make">
            <h2>LET`S WORK TOGETHER</h2>
            <h4>We work as a single united team with marker leadling firms around the world and give our clients the highest quality advice possible</h4>
            <button>MAKE ENQUIRY</button>
        </section>

        <section id="callour">
            <h3>CALL OUR EXPERT TODAY 1.800.555.6789</h3>
            <h5>Copyright 2012-2020   Avada Theme by Theme Fusion   All Rights Reserved   Powered by WordPress</h5>
            <ul class="ul-icons">
               <li><img src="../assets/img/footer-facebook.png" alt="facebook logo"></li>
               <li><img src="../assets/img/footer-twitter.png" alt="twitter logo"></li>
               <li><img src="../assets/img/footer-youtube.png" alt="youtube logo"></li>
            </ul>
        </section>
        
    </div>
</template>

<script>
import ColumnComp from './ColumnComp.vue'
    export default {
        name: 'FootComp',
        components: {
            ColumnComp
        },
        data(){
            return{
                products: [
                    {
                        src: "law_7.jpg",
                        titolo: "INTERNATIONAL",
                        testo: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incidunt ut labore. Sadips ipsums et dolores ficilis ametis uns etras."
                    },
                    {
                        src: "law_8.jpg",
                        titolo: "PARTNERSHIPS",
                        testo: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incidunt ut labore. Sadips ipsums et dolores ficilis ametis uns etras."
                    },
                    {
                        src: "law_3.jpg",
                        titolo: "EXCELLENCE",
                        testo: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incidunt ut labore. Sadips ipsums et dolores ficilis ametis uns etras."
                    },
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>


.columns{
    gap: 1%;
    padding: 100px 200px;
    margin: 100px 100px;
}

#make{
    padding: 100px;
    margin-top: 200px;
    background-image: url(../assets/img/showeare-parallax.jpg);
    color: white;
    text-align: center;
    
    button{
        padding: 10px;
        margin: 10px;
        border: none;
        background-color: #74a59e;
        color: white;
    }
}

#callour{
    padding: 100px;

    h3{
        padding: 10px;
    }
    h5{
        color: gray;
    }

  .ul-icons{
  display: flex;
  float: right;
  padding: 0;
  margin: 0 5px;

  li{
  list-style-type: none;
  margin: 0 5px;
 }

}
}

</style>
