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

        <section>
            
        </section>
        
    </div>
</template>

<script>
    export default {
        name: 'MainComp'
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

</style>