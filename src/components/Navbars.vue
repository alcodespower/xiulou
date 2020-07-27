<!--NavBar-->
<template>
    <van-nav-bar title="KPlayer" @click-left="onClickLeft" @click-right="onClickRight" class="kNavBar" fixed>
        <template #left>
            <van-icon name="apps-o" size="24"/>
        </template>
        <template #right>
                <van-icon name="music-o" size="24" class="music_round"/>
        </template>
    </van-nav-bar>
</template>


<style>
    .music_round {
        animation: music_round 3s linear infinite;
    }
    @keyframes music_round {
        from {-webkit-transform: rotate(0deg);}
        to {-webkit-transform: rotate(360deg);}
    }
</style>

<script>
    import Vue from 'vue';
    import {Toast, NavBar, Icon} from 'vant';

    Vue.use(Toast, Icon, NavBar);
    Vue.use(NavBar);
    Vue.use(Icon);


    export default {
        methods: {
            onClickLeft() {
                Toast('菜单');
            },
            onClickRight() {
                Toast('按钮');
            },
        },
    };
</script>