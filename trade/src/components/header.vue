<!--
 * @Author: your name
 * @Date: 2020-04-04 17:22:10
 * @LastEditTime: 2020-04-04 17:40:02
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \umid:\study\vue\vue\trade\src\components\header.vue
 -->
<template>
    <div class="header">
        <img class="log" src="@/assets/logo.png" />
        <div class="lang">
            <img class="zh" src="@/assets/cn.png" />
            <img class="en" src="@/assets/en.png" />
        </div>
    </div>
</template>
<script>
    export default{
    }
</script>
<style >
.header{
    width:1200px;
    margin: 0 auto;
    height: 120px;
    position: relative;
}
.lang{
    position: absolute;
    right:0;
    top:50%;
    transform: translateY(-50%);
}
.en{
    margin-left: 10px;
}
.en,.zh{
    cursor: pointer;
}
</style>