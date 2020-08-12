<template>
    <div>
        <h1>子路由1</h1>
        <h1>姓名是：{{ $route.params.name }}</h1>
        <h1>年龄是：{{ $route.params.age }}</h1>
    </div>
</template>

<script>
export default {
    data(){
        return {
            detail:{}
        };
    },
    created(){
        console.log(this);
    }
}
</script>