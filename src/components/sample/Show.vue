<template>
    <div>
        <div id="demo" class="carousel slide" data-ride="carousel">

    <!-- Indicators -->
    <ul class="carousel-indicators">
        <li data-target="#demo" data-slide-to="0" class="active"></li>
        <li data-target="#demo" data-slide-to="1"></li>
        <li data-target="#demo" data-slide-to="2"></li>
    </ul>

    <!-- The slideshow -->
            <div class="carousel-inner" >
                <div class="carousel-item active">
                <img src="../../assets/banner1_v1.png" alt="image 1">
                </div>
                <div class="carousel-item">
                <img src="../../assets/banner2_v1.png" alt="Chicago">
                </div>
                <div class="carousel-item">
                <img src="../../assets/banner3_v1.png" alt="New York">
                </div>
        </div>
            <a class="carousel-control-prev" href="#demo" data-slide="prev">
                <span class="carousel-control-prev-icon"></span>
            </a>
            <a class="carousel-control-next" href="#demo" data-slide="next">
                <span class="carousel-control-next-icon"></span>
            </a>

        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    
    .carousel-inner{
        div{
            img{
                display: block;
                margin-left: auto;
                margin-right: auto;
                height: auto;
                max-width: 100%;
            }
        }
    }
</style>