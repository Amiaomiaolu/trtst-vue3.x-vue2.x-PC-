<template>
     <el-container class="container">
        <el-header height="80px">
            <Header />
        </el-header>
        <el-main>
            <div class="layout">
                <router-view></router-view>
            </div>
            <Footer />
            <el-backtop target=".el-main" :bottom="backBottom">
                <img src="./assets/goTop.png" alt="">
            </el-backtop>
        </el-main>
        <Login v-show="loginDialogVisible" />
        <play-bar></play-bar>
    </el-container>
</template>

<script setup>
import Header from '@components/Header.vue'
import Footer from '@components/Footer.vue'
import Login from '@components/Login.vue'
import PlayBar from '@components/PlayBar.vue'
import { computed, ref } from 'vue'
import { useStore } from 'vuex'

const store = useStore();
const loginDialogVisible = computed(() => store.getters.loginDialogVisible);
const backBottom = ref(80);
</script>

<style scoped>
.container {
    height: 100%;
}
.layout {
    min-height: calc(100vh - 80px - 40px);
}
</style>
