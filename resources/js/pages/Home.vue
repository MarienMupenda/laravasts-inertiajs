<template>
    <h1 class="text-3xl font-bold">Home</h1>
    <Nav/>
</template>

<script>

import Nav from "../components/Navbar";

export default {
    name: "Welcome",
    components: {Nav},
    props: {
        name: {
            type: String,
            default: "Marien"
        },
        frameworks: {
            type: Array,
            default: null
        }
    }
}
</script>

<style scoped>

</style>
