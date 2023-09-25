<script>

import comics from '../comics'

export default {
    name: 'componentsContent',

    components: {
        comics
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
                <div class="col-2 mt-5" v-for="item in comics.comics">
                    <div class="card p-2">
                        <img :src="item.thumb" class="card-img-top">
                        <div>
                            <div class="text-white fw-bold">{{ item.series }}</div>
                        </div>
                    </div>
                </div>
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

img {
    height: 220px;
}

.card {
    height: 250px;
    background-color: black;
    border: none;
    text-transform: uppercase;
    font-size: 12px;
}
</style>