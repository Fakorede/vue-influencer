<template>
<Nav />

<main role="main">
    <router-view></router-view>
</main>
</template>

<script>
    import Nav from '@/components/Nav.vue';

    export default {
        name: "Layout",
        components: { Nav },
    }
</script>