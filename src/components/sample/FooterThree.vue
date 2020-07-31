<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#">JUST SKIZZLE</a>
            <button class="navbar-toggler d-lg-none" type="button" data-toggle="collapse" data-target="#collapsibleNavId" aria-controls="collapsibleNavId"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse " id="collapsibleNavId">
                <ul class="navbar-nav mr-auto mt-2 mt-lg-0 justify-content-center">
                    <li class="nav-item" v-for="item in navbar" :key="item">
                        <a class="nav-link" href="#">{{item}}</a>
                    </li>
                </ul>
            </div>
            <span>
                

            </span>
        </nav>
        <main-section></main-section>


        <footer-section></footer-section>
    </div>

</template>

<script>
import Footer from './Footer.vue';
import Main from './main.vue';
export default {
    components:{
        'footer-section' : Footer,
        'main-section' : Main,

    },
    data() {
        return {
            navbar:[
                'Women',
                'Men',
                'Jewellery',
                'Bags & Wallets',
                'Bueaty & Personal Care',

            ],
            men:[

            ],
            women:[

            ],
        }
    },
    
}
</script>

<style>

</style>