<template>
    <div class="hello">
        <ul>
            <li>yo</li>
            <li>zurriago</li>
        </ul>
        <ul>
            <li>tú</li>
            <li>zurriagas</li>
        </ul>
        <ul>
            <li>él\/ella\/Ud.</li>
            <li>zurriaga</li>
        </ul>
        <ul>
            <li>nosotros</li>
            <li>zurriagamos</li>
        </ul>
        <ul>
            <li>vosotros</li>
            <li>zurriagáis</li>
        </ul>
        <ul>
            <li>ellos\/ellas\/Uds.</li>
            <li>zurriagan</li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'VerbeDetail',
        data() {
            return {
                msg: 'Indicativo',
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
