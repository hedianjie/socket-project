<template>
    <div class="nav">
        <div class="nav-main">正在输入中…</div>
        <div class="nav-left"><img src="../../static/img/logo-w.png"/></div>
        <div class="nav-right"></div>
    </div>
</template>
<script>
export default {
    data() {
        return {

        }
    }
}
</script>
<style scoped>
/** layout **/
.nav{
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 50px;
	padding: 10px 70px;
	border-bottom: 1px solid #e1e1e1;
	background: #444;
}
.nav > .nav-main,
.nav > .nav-left,
.nav > .nav-right{
	position: relative;
	float: left;
	height: 30px;
}
.nav > .nav-main{
	width: 100%;
}
.nav > .nav-left{
	width: 70px;
	margin-left: -100%;
	left: -70px;
}
.nav > .nav-right{
	width: 70px;
	margin-left: -70px;
	right: -70px;
}
/** logo **/
.nav > .nav-left{
	font-size: 0;
	text-align: center;
}
.nav > .nav-left img{
	height: 100%;
	width: auto;
	display: inline-block;

}
/** main **/
.nav > .nav-main{
	font-size: 14px;
	letter-spacing: 3px;
	text-align: center;
	line-height: 30px;
	color: #fff;
}
</style>


