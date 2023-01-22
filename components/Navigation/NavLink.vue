<template>
    <a class="nav link" :href="to">{{ text }}</a>
</template>

<script>
export default {
    props: {
        to : String,
        text : String
    }
}
</script>

<style>
    .nav.link {
        color: rgb(196, 196, 196);
        text-decoration: none;
        font-size: 1.5em;
        margin-left: 2vh;
    }
    .nav.link:hover {
        text-decoration: underline;
    }
</style>