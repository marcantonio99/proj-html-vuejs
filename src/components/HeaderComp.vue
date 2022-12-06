<template>
  <div>
    <section id="social">
      <p>Avada & Associates legal team announce deal to open up oil & gas</p>
      <ul class="ul-icons">
        <li><img src="../assets/img/footer-facebook.png" alt="facebook logo"></li>
        <li><img src="../assets/img/footer-twitter.png" alt="twitter logo"></li>
        <li><img src="../assets/img/footer-youtube.png" alt="youtube logo"></li>
      </ul>
    </section>
  
    <section id="img-preview">
    </section>

    <section id="tab">
      <table>
       <tr>
        <th>WHO WE ARE</th>
        <th>WHAT WE DO</th>
        <th>WHERE WE WORK</th>
       </tr>
       <tr>
        <td>Nullam fringilla tristique elit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamus volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.</td>
        <td>Nullam fringilla tristique elit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamus volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.</td>
        <td>Nullam fringilla tristique elit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamus volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.</td> 
       </tr>
       <tr>
        <td><button type="button">LEARN MORE</button></td>
        <td><button type="button">LEARN MORE</button></td>
        <td><button type="button">LEARN MORE</button></td>
       </tr>
      </table>
    </section>

  </div>
</template>

<script>
export default {
  name: 'HeaderComp',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#social{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 200px;
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

#img-preview{
  background-image: url(../assets/img/video_law_home_preview.jpg);
  padding: 250px;
  background-position: 0rem 60rem;
}

#tab{

  table{
    padding: 80px 200px;
    background-color: white;
  }

  th{
    padding: 10px;
  }

  td{
    text-align: center;
    padding: 0 30px;
  }

  button{
    border: none;
    padding: 10px;
    color: white;
    background-color: #30343a;
  }
}


</style>
