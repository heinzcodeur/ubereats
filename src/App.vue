<template>
    <div id="app">
        <!--<img alt="Vue logo" src="./assets/logo.png">
        <HelloWorld msg="Welcome to Your Vue.js App"/>-->
        <!--RestaurantRow v-for="(pipi, i) in 3" :key="i"/-->
        <!--RestaurantCard v-for="(toto,index) in 2" :key="index" /-->
        <!--<ul>
            <li v-for='index in 10' :key='index'>
                <strong>5 * {{index}}  = {{index*5}}</strong>
            </li>
        </ul>-->
        <router-view></router-view>
    </div>
</template>

<script>
    //import HelloWorld from './components/HelloWorld.vue'
    // import RestaurantRow from './components/RestaurantRow.vue'
    //import Home from './page/Home.vue'

    export default {
        name: 'App',
        components: {
            //Home
        }
        /*components: {
          HelloWorld
        }*/
    }
</script>

<style>
    @import url('./style/reset.css');
    @import url('https://fonts.googleapis.com/css2?family=Roboto%3Awght%40300%3B400%3B700&display=swap');

    #app {
        /*font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;*/
        margin-top: -20px;
        padding: 20px;
    }
</style>
