<script>

export default {
    name: 'componentsJumbotron'
}

</script>

<template>
    <div class="position-relative" id="app_jumbotron">
        <div>
            <button class="btn btn-primary rounded-0 position-absolute fw-bold fs-4">CURRENT SERIES</button>
        </div>
    </div>
</template>

<style scoped>
#app_jumbotron {
    width: 100%;
    background-image: url(../assets/img/jumbotron.jpg);
    height: 450px;
}

button {
    top: 95%;
    left: 15%;
}
</style>