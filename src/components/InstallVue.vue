<template>
    <div>
        <div class="comentario">
            <i class="material-icons">comment</i>Install vue-cli
        </div>
        <b-alert show variant="success">npm i -g vue-cli</b-alert>

        <div class="comentario">
            <i class="material-icons">comment</i>Begin a new project
        </div>
        <b-alert show variant="success">vue init bootstrap-vue/webpack-simple NAME_OF_YOUR_PROJECT</b-alert>

        <div class="comentario">
            <i class="material-icons">comment</i>Go to your project
        </div>
        <b-alert show variant="success">cd NAME_OF_YOUR_PROJECT/</b-alert>

        <div class="comentario">
            <i class="material-icons">comment</i>Install dependencies
        </div>
        <b-alert show variant="success"> npm i</b-alert>

        <div class="comentario">
            <i class="material-icons">comment</i>Build your vue app!
        </div>
        <b-alert show variant="success">npm run dev</b-alert>
    </div>
</template>


<script>
    export default {
        name: 'install_vue',
        data () {
            return {
            }
        }
    }
</script>

<style lang="scss">
    .comentario {
        text-align: left;
        color: #2c3e50;
    }
</style>
