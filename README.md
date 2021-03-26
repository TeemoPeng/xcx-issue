# xcx-issue
微信小程序的各种坑 【持续更新】

1. input输入框偏移，在最外层使用scroll-view，scroll-y设置为true
2. 自定义组件中使用wx.createCanvasContext()，第二个参数需要加this（canvasToTempFilePath 也需要）
3. cover-view 不支持iconfont
4. 不要在前端调用wxacode.getUnlimited接口，request合法域名无法添加 "https://api.weixin.qq.com/ "，获取小程序码应由后台来调用该接口，返回arrayBuffer
5. 