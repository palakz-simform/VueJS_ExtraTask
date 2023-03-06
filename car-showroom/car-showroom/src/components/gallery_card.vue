<template>
<div class="card">
    <div class="heading">
        <h1>{{data.name}}</h1>
    </div>
    <div class="image">
        <h1>Image</h1>
    </div>
    <div class="description">
        <h1>{{data.name}}</h1>
    </div>
    <div class="btn">
        <button class="button">a</button>
    </div>
</div>
</template>

<script>
export default {
    name: "gallery_card",
    props: {
        data: Object
    }

}
</script>

<style scoped>
.card {
    border: 1px solid black;
    width: 350px;
    margin: 10px;
}

.heading {
    background-color: aquamarine;
    width: 350px;
    height: 50px;
    text-align: center;
    margin: 0px;
    ;

}

.image {
    background-color: rgb(214, 109, 109);
    width: 350px;
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.description {
    background-color: rgb(119, 119, 218);
    height: 80px;
    width: 350px;
    text-align: center;
}

.btn {
    background-color: green;
    width: 350px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;

}

.button {

    width: 100px;
    height: 34px;
}
</style>
