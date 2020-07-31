<template>  
<div class=" p-5">
    <div class="center">
        <h4>NEW ARRAIVALS</h4>
    </div>
    <div class="new container-fuild">
        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop1.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>
        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop2.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>

        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop3.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>
        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop4.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>

        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop5.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>
        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop6.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>

        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop7.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>
        <div class="nullimage">
            <img class="img-fluid"  src="../../assets/photos/shop8.jpeg" alt="">
            <p><i>Name</i></p>
            <p>  </p>
        </div>
    </div>
</div>


</template>

<script>

export default {
    data() {
        return {
                
        }
    },
    methods: {

    },
}
</script>
<style lang="scss">

    .center{
        text-align: center;
        font-weight: bold;
        padding: 4em;
    }
    .new{
       display: grid;
       grid-template-columns: repeat(4 ,1fr);
       .nullimage{               
        height: 470px;
        width: auto;
        display: block;
        text-align: center;
            img{
                 object-fit: contain;
                width: 100%;
                height: 80%;
            }
       }
    }
    @media  screen and (max-width: 600px){
        .center{
            padding: 1em;
        }
        .new{
            grid-template-columns: repeat(1,1fr);
            .nullimage{
            margin-top: 1em;
            margin-bottom:1em;
            }
        }
    }
</style>