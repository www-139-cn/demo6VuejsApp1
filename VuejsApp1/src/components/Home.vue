
<template>
    <!--meta charset="utf-8"-->
    <div class="home">
        <h1>{{ msg }}</h1>
        欢迎光临山哥的网址, built with <a href="https://vuejs.org" target="_blank">Vue.js</a>.
        {{ msg1 }}
    </div>
</template>

<script>
    export default {
        name: 'Home',
        props: {
            msg: String
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
