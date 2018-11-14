<template>
    <div id="app">
        <img src="./assets/logo.png">
        <!-- <VerbeFiche /> -->
        <div>
            <div style="color: red" v-for="app in verbos"><span> {{app.verbo}} </span>
                <div style="color: blue" v-for="(temps, key) in app" v-show="key != 'verbo'" >{{key}}
                    <div style="color: green" v-for="(mode, val) in temps">  {{val}}
                        <div style="color: grey" v-for="(detail, cle) in mode">{{cle}} {{detail}}
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import VerbeFiche from './components/VerbeFiche';
    import verbosJson from '../data/zurriagar.json'

    export default {
        name: 'App',
        components: {
            VerbeFiche,
        },
        data() {
            return {
                verbos: verbosJson.verbos,
            };
        },
    };

</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }

    ,
    .verbo {
        color: red;
    }

    ,
    .temps {
        color: blue;
    }

    ,
    .mode {
        color: green;
    }

</style>
