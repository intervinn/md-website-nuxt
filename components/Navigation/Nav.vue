
<template>
    <div class="nav">
        <NavHeader/>
        <NavLink text="about" to="/about"/>
        <NavLink text="apply" to="/apply"/>
    </div>
</template>

<script>
import NavLink from './NavLink.vue';
import NavHeader from './NavHeader.vue';

export default {
    components: {
        NavLink,
        NavHeader
    }
}
</script>

<style>

    .nav {
        display: flex;
        flex-direction: row;
        align-items: center;
        background-color: rgb(42, 35, 42);
        height: 10vh
    }
</style>