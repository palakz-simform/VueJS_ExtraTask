<template>
<div class="title">
    <h1>Car Gallery</h1>
</div>

<div class="car-card">
    <div v-for="item in cars_info" :key="item.id">
        <gallery_card :data="item" />
    </div>

</div>
</template>

<script>
import gallery_card from "./components/gallery_card.vue"

export default {
    name: "App",
    components: {
        gallery_card,

    },
    data() {
        return {
            cars_info: [{
                    id: 1,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 2,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 3,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 4,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 5,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 6,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 7,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 8,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 9,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },
                {
                    id: 10,
                    name: "Toyota",
                    image: "",
                    desc: "",
                    price: ""
                },

            ]
        }
    }
}
</script>

<style>
.car-card {
    display: flex;
    ;
    flex-wrap: wrap;
    justify-content: center;
}

.title {
    text-align: center;
}

.title h1 {
    color: brown;
    text-decoration: underline;
}
</style>
