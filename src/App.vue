<template>
    <div id="app">
        <h1 class="b">企业不缺人，缺的是人才!</h1>
        <h1 class="b" id="a">扩展自我知识，增强自我竞争力!</h1>
        <h1 class="b">实现人无我有，做到人有我优!</h1>
        <h1 class="b">----------------------------------</h1>
        <h1 class="b">只有努力奔跑,才能保持原地不动,不然就是落后 </h1>
        <p v-cloak>{{msg}}</p>
        <p v-html="msg1"></p>
    </div>
</template>

<script>
    export default {
        name: "APP",
        data(){
           return{
               msg:'123456',
               msg1:'<h1>我大，哈哈</h1>'
           }
        }

    }
</script>

<style scoped>
    .b{
        color: red;
    }
    #a{
        #background-color: aqua;
    }
</style>
