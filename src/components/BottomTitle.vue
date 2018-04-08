<template>
    <b-container class="p-1 bg-dark col-12 letrero">
        <b-row>
            <b-col>
                <b-img class="smallImg" rounded="circle"
                       src="https://images.vexels.com/media/users/3/143149/isolated/preview/483853fc9aa104651cf909e32c62475b-golden-stamp-post-by-vexels.png"
                       alt="Thumbnail"/>
            </b-col>
            <b-col>
                <b-img class="smallImg" rounded="circle" src="https://bootstrap-vue.js.org/_nuxt/img/icon.f0a8c9e.png"
                       alt="Thumbnail"/>
            </b-col>
            <b-col>
                <h1 class="smallTxt" style="color: aquamarine">TUTORIAL</h1>
            </b-col>
        </b-row>
    </b-container>
</template>


<script>
    export default {
        name: 'bottomTitle',
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
</style>
