<template>
    <div>
        <Nav/>
        <NuxtPage/>
    </div>
</template>

<script>
import Nav from '~~/components/Navigation/Nav.vue';

export default {
    components: {
        Nav
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');

html, body {
  margin: 0;
  font-family: 'Nunito', sans-serif;
}
</style>