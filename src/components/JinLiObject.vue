<template>
<!--    导航条开始-->
<!--    最外层的大盒子-->
    <div class="nav">
<!--        水平居中的盒子-->
        <div class="wrap">
<!--            左侧盒子-->
            <div class="logo">
                <a href="#">
                <img src="../img/jinLiImage/logo.png" alt="">
                </a>
            </div>
<!--            右侧盒子-->
            <div class="nav-bar">
<!--                上面的盒子-->
                <div class="nav-bar-top">
                    <ul>
                        <li><a href="#" class="active">amigo账号</a><span>|</span></li>
                        <li><a href="#">原账号</a><span>|</span></li>
                        <li><a href="#">注册</a></li>
                        <li><a href="#" class="cart">购物车(0)</a></li>
                    </ul>
                </div>
<!--                下面的盒子-->
                <div class="nav-bar-bottom">
                    <ul>
                        <li><a href="#">首页</a></li>
                        <li><a href="#">手机</a></li>
                        <li><a href="#">配件</a></li>
                        <li><a href="#">服务</a></li>
                        <li><a href="#">下载</a></li>
                        <li><a href="#">amigoOS</a></li>
                        <li class="form">
                            <form action="">
                                <input type="text" placeholder="输入搜索内容" >
                                <a href="#"><button>镜</button></a>
                                <div class="search"></div>
                            </form>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "JinLiObject"
    }
</script>

<style scoped>


</style>