<template>
    <div class="footer">
        <div class="toolbar">
            <a class="web_face" href="javascript: void(0);"></a>
            <a class="web_file" href="javascript: void(0);"></a>
        </div>
        <div class="content">
            <div class="contentable" contenteditable="true"></div>
        </div>
        <div class="action">
            <span class="desc">按下Cmd+Enter换行</span>
            <a href="javascript: void(0)" class="btn_send">发送</a>
        </div>
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
    .footer{
        border-top: 1px solid #d6d6d6;
        background: #eee;
        height: 180px;
    }
    .toolbar{
        padding: 5px 17px;
    }
    .toolbar .web_face,
    .toolbar .web_file{
        display: inline-block;
        vertical-align: middle;
       
        width: 30px;
        height: 30px;
    }
    .toolbar .web_face{
        background: url(//res.wx.qq.com/a/wx_fed/webwx/res/static/css/3d77c66cd37282eb9aae25295f7b0302@2x.png) no-repeat;
        background-position: -404px -398px;
         background-size: 487px 462px;
    }
    .toolbar .web_file{
        background: url(//res.wx.qq.com/a/wx_fed/webwx/res/static/css/3d77c66cd37282eb9aae25295f7b0302@2x.png) no-repeat;
        background-position: -120px -432px;
         background-size: 487px 462px;
    }

    .content{
        padding: 0 20px;

    }
    .contentable{
        outline: none;
        font-size: 14px;
        height: 84px;
        overflow-x: hidden;
        overflow-y: auto;
        border: 0;
        white-space: pre-wrap;
    }
    .action{
        margin-top: 5px;
        text-align: right;
        padding: 0 20px;
    }
    .desc{
        color: #888888;
        font-size: 12px;
        margin-left: 10px;
        margin-right: 7px;
    }
    .btn_send{
        text-decoration: none;
        color: #222;
        padding-left: 30px;
        padding-right: 30px;
        padding-top: 3px;
        padding-bottom: 2px;
        border: 1px solid #c1c1c1;
        border-radius: 4px;
        background: #fff;
        display: inline-block;
    }
    .btn_send:hover{
        background: #f8f8f8;
    }
</style>


