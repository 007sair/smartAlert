# smartAlert
小弹层

## 调用

```js
salt({
    msg: '这是弹层信息文字',
    buttonText: '确定', //弹层按钮文本
    isShowConfirmButton: true, //是否显示按钮
    zIndex: 1000,
    fnShow: function() {}, //弹层弹出时触发
    fnHide: function() {}, //弹层关闭时触发
    fnConfirmClick: function() {} //弹层"确定"按钮被点击时触发
});
```
