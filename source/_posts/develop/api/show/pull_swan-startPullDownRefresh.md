---
title: swan.startPullDownRefresh
header: develop
nav: api
sidebar: pull_swan-startPullDownRefresh
---
 
 
**解释**：开始下拉刷新，调用后触发下拉刷新动画，效果与用户手动下拉刷新一致。

**百度APP中扫码体验：**

<img src="https://b.bdstatic.com/miniapp/assets/images/doc_demo/pullDownRefresh.png"  class="demo-qrcode-image" />

**方法参数**：Object object

**`object`参数说明**：

|参数名 |类型  |必填 | 默认值 |说明|
|---- | ---- | ---- | ----|----|
|success| Function |   否  | |接口调用成功的回调函数|
|fail   | Function |   否  | |接口调用失败的回调函数|
|complete  |  Function  |  否  | | 接口调用结束的回调函数（调用成功、失败都会执行）|

**示例**：

<a href="swanide://fragment/37955e937e5e221c983f1129861c38ae1569476821334" title="在开发者工具中预览效果" target="_self">在开发者工具中预览效果</a>

* 在 js 文件中

```js

    swan.startPullDownRefresh({
        success: res => {
            console.log('startPullDownRefresh success');
        },
        fail: err => {
            console.log('startPullDownRefresh fail', err);
        }
    });
  
```



#### 错误码
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败  |

* iOS

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|
 
