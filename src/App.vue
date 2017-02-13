<template>
<div id="app">
    <h1>{{message}}</h1>
</div>
</template>

<script>
export default {
    name: 'app',
    data(){
        return {};
    },
    // 父级组件传过来的值
    props:['message'],
}
</script>

<style>

</style>
