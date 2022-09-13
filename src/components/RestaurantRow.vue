<template>
    <div class="restaurant--row">
        <h2 class="title">Nos restaurants</h2>
        <div class="wrapper--card">
            <RestaurantCard v-for="(toto, i) in three_restaurant" :info_restaurant="toto" :key="i"/>
        </div>
    </div>
    <hr>
</template>


<script>
    import RestaurantCard from "./RestaurantCard.vue";

    export default {
        name: "RestaurantRow",
        components: {
            RestaurantCard,
        },
        props: {
            three_restaurant: Array
        }
    }

</script>

<style lang="scss">
    .restaurant--row {
        .wrapper--card {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
    }
</style>