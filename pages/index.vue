<template>
    <main>
        <h1 class="red">Hello world!</h1>
        <NuxtLink to="/more-fun">internal link</NuxtLink>
        <a href="https://nuxtjs.org">External link</a>
    </main>
</template>

<script>
    export default {
        head() {
            //meta tag
        }
    }
</script>

<style>
    .red {
        color: red;
    }
</style>