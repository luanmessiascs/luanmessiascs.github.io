<template>
    <Menu />
    <div id="content">
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
        left: 2px;
        width: 822px;
        height: 100%;
        margin-left: 200px;
        border: 2px solid black;
        padding: 10px;
    }
</style>