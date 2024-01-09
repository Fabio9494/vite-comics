<script>
export default {
    name: 'CardFumetti',
    props: {
        fumetto: Object
    }
}
</script>

<template lang="">
    <div class="card" :key="index">
        <img :src="fumetto.thumb" alt="">
        <h5>{{fumetto.series}}</h5>
    </div>
</template>
<style lang="scss" scoped>
.card {
    width: calc(100% / 6 - 20px);
    color: white;

    img {
        width: 80%;
        height: 200px;
    }
}
</style>