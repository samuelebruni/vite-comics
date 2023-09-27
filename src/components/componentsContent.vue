<script>

import comics from '../comics'
import componentsItem from './componentsItem.vue'

export default {
    name: 'componentsContent',

    components: {
        comics,
        componentsItem
    },

    data() {
        return {
            comics
        }
    }
}
</script>

<template>
    <section id="app_products">

        <div class="container">

            <div class="row d-flex pb-5">
                <componentsItem :item="item" v-for="item in comics.comics" />
            </div>
            <div class="d-flex align-items-center justify-content-center pb-5">
                <button class="btn btn-primary rounded-0 fw-bold">LOAD MORE</button>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    background-color: black;
}
</style>