<template>
    <div class="hello">
        <h2>{{ temps }}</h2>
        <VerbeMode />
    </div>
</template>

<script>
    import VerbeMode from './VerbeMode';

    export default {
        name: 'VerbeTemps',
        components: {
            VerbeMode,
        },
        data() {
            return {
                temps: 'Indicativo',
            };
        },
    };

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1,
    h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }

</style>
