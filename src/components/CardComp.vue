<template>
    <div class="card">
        <img src="dettagliCard.src" alt="">
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
    background-color: lightgray;
    padding: 20px;
    width: calc(99% / 3);

h4{
    text-align: right;
    justify-content: space-around;
    display: flex;
    float: right;
    padding-top: 40px;

}
}
</style>