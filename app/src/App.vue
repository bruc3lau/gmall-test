<template>
    <div id="app">
        <Header a="a from root"></Header>
        <!-- main -->
        <router-view></router-view>
         <Footer></Footer>
    </div>
</template>

<script>
import Header from './components/Header/Header.vue'
import Footer from './components/Footer/Footer.vue'
export default {
    name: 'App',
    components: {
        Header: Header,
        Footer: Footer
    },
    methods: {
        test() {
            alert(555)
        }
    }
}
</script>

<style>
</style>
