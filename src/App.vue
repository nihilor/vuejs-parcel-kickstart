<template>
    <div id="app">
        <h1>{{ title }}</h1>
        <p>{{ description }}</p>
    </div>
</template>

<script>
export default {
    name: 'app',
    data() {
        return {
            title: 'Vue.js and Parcel.js Kickstart',
            description: 'A simple but complete kickstart scaffold for Vue.js and Parcel with Babel and Eslint.'
        }
    }
}
</script>

<style lang="css">
body {
    color: #34495e;
}
h1 {
    color: #41b883;
}
</style>