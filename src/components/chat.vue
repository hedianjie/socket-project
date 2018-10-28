<template>
    <div class="main">
        <div class="tip"><span class="ls-tip">17:56</span></div>
        <div class="sid left">
            <div class="avatar"><img src="../../static/img/logo-w.png" alt=""></div>
            <div class="message">
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
                dsflaskdlfjalskfjals
            </div>
            <div class="status"></div>
        </div>
        <div class="sid right">
            <div class="avatar"><img src="../../static/img/logo-w.png" alt=""></div>
            <div class="message">
                dsflaskdlfjalskfjals
            </div>
            <div class="status"></div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .main{
        height: 100%;
        overflow-x: hidden;
        overflow-y: auto;
        padding: 0 20px;
        padding-top: 20px;
        background: #f0f0f0;
        
    }
    .main .sid{
        color: #333;
        position: relative;
        margin-bottom: 16px;
        width: 70%;
    }
    .tip{
        margin-bottom: 16px;
        width: 100%;
        text-align: center;
    }
    .tip .ls-tip{
        padding: 1px 16px;
        font-size: 12px;
        color: #333;
        background: transparent;
        border-radius: 100px;
        letter-spacing: 1px;
        line-height: 1.6;
        color: #b2b2b2;
    }
    .avatar{
        position: absolute;
        width: 40px;
        height: 40px;
        display: inline-block;
        vertical-align: top;
    }
    .message{
        padding: 9px 15px;
        font-size: 14px;
        position: relative;
        vertical-align: top;
        border-radius: 4px;
        display: inline-block;
        word-break: pre-wrap;
        line-height: 22px;        
    }
    .message:before{
        content: "";
        position: absolute;
        width: 0;
        height: 0;
        border: 7px solid #000000;
        border-radius: 2px;
    }

    .left{
        padding-left: 55px;
        float: left;
    }
    .left .avatar{
        left: 0;
        top: 0;
    }
    .left .message{
        float: left;
        color: #333;
        background: #fff;
    }
    .left .message:before{
        left: -13px;
        top: 15px;
        border-color: transparent #fff  transparent transparent;
        
    }
    .right{
        padding-right: 55px;
        float: right;
    }
    .right .avatar{
        right: 0;
        top: 0;
    }
    .right .message{
        float: right;
        color: #fff;
        background: #2d8cf0;
    }
    .right .message:before{
        right: -13px;
        top: 14px;
        border-color: transparent transparent  transparent #2d8cf0;
    }
    
</style>


