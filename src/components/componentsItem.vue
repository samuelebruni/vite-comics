<script>
export default {
    name: 'componentsItem',
    props: {
        item: Object
    }
}
</script>

<template>
    <div class="col-2 mt-5">
        <div class="card p-2">
            <img :src="item.thumb" class="card-img-top">
            <div>
                <div class="text-white fw-bold">{{ item.series }}</div>
            </div>
        </div>
    </div>
</template>

<style scoped>
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