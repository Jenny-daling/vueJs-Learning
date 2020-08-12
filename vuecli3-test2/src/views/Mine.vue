<template>
    <div>
        <h1>这是我自定义的页面</h1>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped lang="scss">
    $bg:#f00;
    h1{
        float:left;
        background: $bg;
    }
</style>