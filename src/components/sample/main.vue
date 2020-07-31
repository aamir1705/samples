<template>
    <div>
        <show-item></show-item>
        <new-arrivals></new-arrivals>
        <water-mark></water-mark>
        <treading-now></treading-now>
        <div class="container-fluid">
            <div class="strip" style="background-color:#34675c">
                MEN'S
            </div>
            <div class="strip" style="background-color:#b7b8b6">
                WOMEN'S
            </div>
            <div class="strip" style="background-color:#4CB5F5">
                DOWNLOAD THE APP 
            </div>
        </div>

    </div>
</template>

<script>
import Show from './Show.vue';
import NewArrivals from './NewArrivals.vue';
import WaterMark from './WaterMark.vue';
import TrendingNow from './TrendingNow.vue';

export default {
    components:{
        "show-item":Show,
        'new-arrivals':NewArrivals,
        'water-mark': WaterMark,
        'treading-now': TrendingNow,
    }
}
</script>

<style lang="scss">
    .strip{
        margin-top: 2em;
        margin-bottom: 2em;
        display: flex;
        justify-content: center;
        align-items: center;
        color:white;
        height: 100px;
        font-size: 1.4em;
    }
</style>