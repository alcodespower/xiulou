<template>
    <div class="home">
        <kNavbars></kNavbars>
        <kSwiper></kSwiper>
        <kGrid></kGrid>
        <kFooter></kFooter>
    </div>
</template>

<style>

</style>

<script type="text/javascript">
    import kNavbars from '../components/kNavbar.vue'
    import kFooter from '../components/kFooter.vue'
    import kSwiper from '../components/kSwiper.vue'
    import kGrid from '../components/kGrid.vue'


    export default {
        data() {
            return {}
        },
        components: {
            kNavbars,
            kFooter,
            kSwiper,
            kGrid
        }

    }
</script>