<template>
    <div id="app">
        {{ message }}
    </div>
</template>

<script>
export default {
    data() {
        return {
            message: 'Hello world!'
        }
    }
}
</script>

<style scoped>
#app {
    font-size: 18px;
    font-family: 'ROboto', sans-serif;
    color: blue;
}
</style>