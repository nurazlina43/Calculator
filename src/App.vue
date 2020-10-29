<template>
<div id="app">
    <heading />
    <calculator />
</div>
</template>

<script>
import heading from './components/heading.vue'
import calculator from './components/calculator.vue'
export default {
    name: 'App',
    components: {
        heading,
        calculator
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 30px;
}
</style>
