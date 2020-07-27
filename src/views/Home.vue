<template>
    <div class="home">
        <Navbars></Navbars>
        <kSwiper></kSwiper>
        <kGrid></kGrid>
        <Footer></Footer>
    </div>
</template>

<style>

</style>

<script type="text/javascript">
    import Navbars from '../components/Navbars.vue'
    import Footer from '../components/Footer.vue'
    import kSwiper from '../components/kSwiper.vue'
    import kGrid from '../components/kGrid.vue'


    export default {
        data() {
            return {}
        },
        components: {
            Navbars,
            Footer,
            kSwiper,
            kGrid
        }

    }
</script>