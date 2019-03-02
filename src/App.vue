<template>
    <main id="app">
        <header>
            <nav-component></nav-component>
        </header>

        <router-view />

        <footer>
            <!--<img src="assets/insta.svg" />
            <img src="assets/dribbble.svg" />
            <img src="assets/linkedin.svg" />
            <img src="assets/twitter.svg" />
            <img src="assets/facebook.svg" />-->
        </footer>
    </main>
</template>
<script type="text/javascript">
    import Nav from './components/nav';

    export default {
        components: {
            'nav-component': Nav
        }
    }
</script>
<style lang="scss">

    @import '@/scss/main.scss';
</style>
