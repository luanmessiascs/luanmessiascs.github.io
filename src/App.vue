<template>
    <Menu />
    <div class="w-75" id="content">
        <router-view></router-view>
    </div>
</template>
<script>
    import Menu from './components/Menu.vue'

    export default {
        components: {
            Menu
        }
    }
</script>
<style scoped>
    div#content {
        position: absolute;
        top: 0px;
        margin-left: 25%;
        height: 100%;
        border: 2px solid black;
        padding: 10px;
    }
</style>