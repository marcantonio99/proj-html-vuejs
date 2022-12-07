<template>
    <div class="column">
        <img :src="dettagliColumn.src" alt="columnphoto">
        <h4>{{ dettagliColumn.titolo }}</h4>
        <p>{{ dettagliColumn.testo }}</p>
    </div>
</template>

<script>
    export default {
        name: 'ColumnComp',
        props: {
            dettagliColumn: Object
        }
    }
</script>

<style lang="scss" scoped>
.column{
    padding: 30px;
    width: calc(99% / 3);
    float: right;
    text-align: center;
}

</style>