<template>
    <div class="hello">
        <h3>{{ mode }}</h3>
        <VerbeDetail />
    </div>
</template>

<script>
    import VerbeDetail from './VerbeDetail';

    export default {
        name: 'VerbeMode',
        components: {
            VerbeDetail,
        },
        data() {
            return {
                mode: 'Presente',
            };
        },
    };

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1,
    h2,
    h3 {
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
