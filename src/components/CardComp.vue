<template>
    <div class="card">
        <img :src="dettagliCard.src" alt="cardphoto">
        <h4>{{ dettagliCard.titolo }}</h4>
    </div>
</template>

<script>
    export default {
        name: 'CardComp',
        props: {
            dettagliCard: Object
        }
    }
</script>

<style lang="scss" scoped>

.card{
    background-color: #ebe9e7;
    padding: 30px;
    margin: 5px 0;
    width: calc(99% / 3);

h4{
    text-align: right;
    justify-content: space-between;
    display: flex;
    float: right;
    

}
}
</style>