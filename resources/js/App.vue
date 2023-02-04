<template>
    <App-header />

    <router-view />

    <App-footer />
</template>

<script>
import Header from "@/component/partial/Header.vue";
import Footer from "@/component/partial/Footer.vue";

export default {
    name: "App",
    components: {
        "App-header": Header,
        "App-footer": Footer,
    },
};
</script>
