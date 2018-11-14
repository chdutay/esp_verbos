<template>
    <div class="hello">
        <h1>{{ Verbe }}</h1>
        <VerbeTemps />
    </div>
</template>

<script>
    import VerbeTemps from './VerbeTemps';

    export default {
        name: 'VerbeFiche',
        components: {
            VerbeTemps,
        },
        data() {
            return {
                Verbe: 'Zurriaga',
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
