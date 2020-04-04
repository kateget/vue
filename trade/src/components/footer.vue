<template>
    <div class="flooter">
        <ul >
            <li>
                走进中科
                <ul class="company">
                    <li >公司简介</li>
                    <li >企业文化</li>
                    <li >发展历程</li>
                    <li >组织架构</li>
                    <li >合作伙伴</li>
                </ul>
            </li>
            <li>主营业务
                <ul class="company2">
                    <li>进口业务</li>
                    <li>出口业务</li>
                    <li>供应链业务</li>
                    <li>代理招标业务</li>
                    <li>离岸业务</li>
                </ul>
            </li>
            <li>企业荣誉
                <ul class="company3">
                    <li>企业资质</li>
                </ul>
            </li>
            <li>售后服务
                <ul class="company4">
                    <li>服务特色</li>
                </ul>
            </li>
            <li>广东省中科进出口有限公司
                <ul class="company5">
                    <li>地址：广东省广州市先烈中路100号科学院9号一楼</li>
                    <li>电话：+86(0)20-3765 6268</li>
                    <li>传真：+86(0)20-8768 2371  +86(0)20-8768 1505</li>
                    <li>网址：http://www.gdstie.com</li>
                    <li>邮箱：shengz_k@gdstie.com</li>
                    <li>邮编：510070</li>
                </ul>
            </li>
        </ul>
    </div>
</template>
<script>

</script>
<style>
*{
    margin: 0;
}
.flooter{
    padding: 50px 0px;
    margin-top: 10px;
    background: #36383e;
    color:#fff;
    font-size: 16px;
    display: inline-block;
    width: 100%;
}
.company,.company2,.company3,.company4,.company5{
    color:#ccc;
    font-size: 14px;
    padding: 0;
    text-align: left;
    line-height: 30px;
    position: relative;
}
.company li,.company2 li,.company3 li,.company4 li{
    position: relative;
}
.flooter > ul > li:last-child{
    width: 400px;
}
.flooter > ul > li{
    
    width:180px;
    float: left;
    text-align: left;
    line-height: 36px;
}
.flooter li{
    list-style: none;
}
.flooter > ul{
    display: block;
    margin: 0 auto;
    width: 1200px;
}
.company li::before,.company2 li::before,.company3 li::before,.company4 li::before{
    display: block;
    content: ".";
    left: -10px;
    line-height: 20px;
    position: absolute;
}
</style>