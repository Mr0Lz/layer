# layer   
IE8,主流浏览器,移动端的弹出框插件 (响应式)


引入js文件

    <script type="text/javascript" src="carousel.js"></script>

1.使用: 提示信息 是innerHtml
msg提示层

    layer.msg('msgmsgmsgmsgmsgmsgmsgms');
    
alert 弹出确定层


    layer.alert({titleText:"yes or no title",//标题
     yesBtnText:"yes",//确定按钮
     noBtnText:"no",//取消按钮
     closeBtnText:"close",//关闭按钮
     contentText:"contentTextcontentTextcontentTextcontentTextcontentTextc",//提示信息
     clearDefaultCss:false,//不使用默认样式,默认false
     yesCall:function () {//点击确认按钮回调
     
    }
    });


### 样式自定义   

1.js清除默认样式 2.然后修改以下css表


    clearDefaultCss:true;

msg提示层的classname 

    .layer-msg


alert弹出确定层的classname


    .layer-alert
    .layer-title
    .layer-close
    .layer-content
    .layer-yesBtn
    .layer-noBtn
