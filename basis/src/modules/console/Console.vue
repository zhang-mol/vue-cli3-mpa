/**
*
* @author louie
* @date created in 2018-10-8 22:48
*/
<template>
    <div id="console" v-wechat-title="$route.meta.title">
        多页面1
        <router-view></router-view>
    </div>
</template>

<script>
    export default {
        name: "console"
    }
</script>

<style scoped>

</style>