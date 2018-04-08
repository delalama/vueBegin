<template>
    <div class="row col-12 f">
        <div>
            <b-card img-src="https://media.giphy.com/media/J82X6zfPVkLuM/giphy.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    This framework is very intuitive
                </p>
            </b-card>
        </div>

        <div>
            <b-card img-src="https://static.diariouno.com.ar/adjuntos/212/imagenes/023/186/0023186115.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    Very very small size
                </p>
            </b-card>
        </div>

        <div>
            <b-card img-src="https://media.giphy.com/media/10bdAP4IOmoN7G/giphy.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    You´ll have to increase your JS skills
                </p>
            </b-card>
        </div>


        <div>
            <b-card img-src="https://media.giphy.com/media/3o7rbG6Wor8JdrHziw/giphy.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    Simple integration, it's JS!
                </p>
            </b-card>
        </div>


        <div>
            <b-card img-src="https://media.giphy.com/media/l0ExmLP9Cw1PQbv32/giphy.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    Very big community to solve your problems
                </p>
            </b-card>
        </div>


        <div>
            <b-card img-src="https://media.giphy.com/media/nXxOjZrbnbRxS/giphy.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    Clear console messages
                </p>
            </b-card>
        </div>

        <div>
            <b-card img-src="https://media.giphy.com/media/HdcimOKferlkI/giphy.gif"
                    img-alt="Image"
                    tag="article"
                    class="mb-2 ">
                <p class="card-text">
                    Extremely fast rendering!
                </p>
            </b-card>
        </div>


    </div>
</template>


<script>
    import { Card } from 'bootstrap-vue/es/components';
    import Vue from 'vue'

    Vue.use(Card);

    export default {
        name: 'whyVue',
        data () {
            return {
            }
        }
    }
</script>

<style lang="scss">
    .smallImg {
        height: 120px;
    }

    .card-img {
        width: 400px;
        height: 308px;
    }
    /*#f {*/
        /*margin: auto;*/
        /*margin-top: auto;*/
        /*width: 50%;*/
        /*padding: 10px;*/
    /*}*/
</style>
