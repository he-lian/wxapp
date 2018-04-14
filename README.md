# wxapp
weixin app snippet for sublime


### 待处理问题：
	1、emmet连写实现
	2、'.class'、'#id'将class/id名字自动填入


### 更新：2018-04-14
	1、配置scope，移除标签书写时的w开头
	2、增加.与#简写方式




### 版权说明
此代码初始版本源自： [Abbotton](https://github.com/Abbotton/weapp-snippet-for-sublime-text-2-3)，
原作者自2016年11月15日后停止更新，而工作中又比较需要，特接手过来进行维护（2018.04.14）






#### WXML snippet

| 命令 | 对应组件或命令 |
| -----|----:|
| app | [注册小程序](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/app.html) |
| button | [button](https://mp.weixin.qq.com/debug/wxadoc/dev/component/button.html) |
| checkbox | [checkbox][2] |
| checkboxgroup | [checkbox-group][2] |
| canvas | [canvas](https://mp.weixin.qq.com/debug/wxadoc/dev/component/canvas.html#canvas) |
| image |[image](https://mp.weixin.qq.com/debug/wxadoc/dev/component/image.html)|
| text | [text](https://mp.weixin.qq.com/debug/wxadoc/dev/component/text.html) |
| text. | [text](https://mp.weixin.qq.com/debug/wxadoc/dev/component/text.html) |
| view | [view][4] |
| . | [view][4] |
| # | [view][4] |
| viewbind | [view 事件](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/event.html) |
| map | [map](https://mp.weixin.qq.com/debug/wxadoc/dev/component/map.html)|
| nav |[navigator](https://mp.weixin.qq.com/debug/wxadoc/dev/component/navigator.html)|
| export | [模块化](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/module.html)|
| for | [for](https://mp.weixin.qq.com/debug/wxadoc/dev/view/wxml/data.html) |
| form |[form](https://mp.weixin.qq.com/debug/wxadoc/dev/component/form.html)|
| radio|[radio][5]|
| radiogroup|[radio-group][5]|
| slider|[slider](https://mp.weixin.qq.com/debug/wxadoc/dev/component/slider.html)|
| icon|[icon](https://mp.weixin.qq.com/debug/wxadoc/dev/component/icon.html)|
| if | [block wx:if](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/conditional.html)  |
| input|[input][3]|
| inputfull|[input][3]|
| textarea|[textarea](https://mp.weixin.qq.com/debug/wxadoc/dev/component/textarea.html)|
| infutautofocus|[input][3]|
| video|[video](https://mp.weixin.qq.com/debug/wxadoc/dev/component/video.html)|
| inputfocus|[input][3]|
| label|[label](https://mp.weixin.qq.com/debug/wxadoc/dev/component/label.html)|
| page|[Page()](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/page.html)|
| progress|[progress](https://mp.weixin.qq.com/debug/wxadoc/dev/component/progress.html)|
| scrollview|[scroll-view](https://mp.weixin.qq.com/debug/wxadoc/dev/component/scroll-view.html)|
| switch|[switch](https://mp.weixin.qq.com/debug/wxadoc/dev/component/switch.html)|
| template|[template](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/template.html)|
| swiper|[swiper](https://mp.weixin.qq.com/debug/wxadoc/dev/component/swiper.html)|


#### 小程序API snippet

| 命令 | 对应组件或命令 |
| -----|----:|
| apirequest| [网络请求](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-request.html) | 
| apiuploadfile| [上传文件][15] | 
| apidownloadfile| [下载文件][15] | 
| apiconnskt| [创建 WebSocket 链接][14] | 
| apionsktopen| [监听WebSocket连接打开][14] | 
| apionskterr| [监听WebSocket错误][14] | 
| apisendsktmsg| [使用 WebSocket发送数据][14] | 
| apionsktmsg| [接受消息推送][14] | 
| apicloseskt| [关闭WebSocket连接][14] | 
| apionsktclose| [监听WebSocket关闭][14] | 
| apichooseimg| [选额图片][13] | 
| apipreviewimg| [预览图片][13] |
| apigetimginfo| [获取图片信息][13] |
| apistartrecord| [开始录音][12] | 
| apistoprecord| [结束录音][12] | 
| apiplayvoice| [播放语音][1] | 
| apipausevoice| [暂停播放语音][1] | 
| apistopvoice| [结束播放语音][1] | 
| apigetbgaudioplayerstate| [获取音乐播放状态][6] | 
| apiplaybgaudio| [播放音乐][6] | 
| apipausebgaudio| [播放暂停音乐][6] | 
| apiseekbgaudio| [控制音乐播放进度][6] | 
| apistopbgaudio| [停止播放音乐][6] | 
| apionbgaudioplay| [监听音乐播放][6] | 
| apionbgaudiopause| [监听音乐暂停][6] | 
| apionbgaudiostop| [监听音乐停止][6] | 
| apisavefile| [保存文件][16] | 
| apigetsavedfilelist | [查看保存文件列表][16] |  
| apigetsavedfileinfo| [查看保存文件信息][16] | 
| apirmfile| [删除缓存文件][16] | 
| apiopendoc| [新开页面打开文档][16] | 
| apichoosevideo| [视频](https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-video.html) | 
| apisetstorage| [覆盖本地内容][7] | 
| apisetstoragesync| [同步覆盖本地内容][7] | 
| apigetstorage| [获取指定 key 对应的内容][7] | 
| apigetstoragesync| [同步获取指定 key 对应的内容][7]  | 
| apiclearstorage| [清理本地数据][7] | 
| apiclearstoragesync| [同步清理本地数据][7]| 
| apirmstorage| [删除本地数据][7]| 
| apirmstoragesync| [同步删除本地数据][7]| 
| apigetstorageinfo| [获取本地数据信息][7]| 
| apigetstorageinfosync| [同步获取本地数据信息][7]| 
| apigetlocation| [获取位置][8] | 
| apiopenlocation| [查看位置][8] | 
| apichooselocation| [打开地图选择位置][8] | 
| apigetnetworktype| [网络状态][9] | 
| apigetsysinfo| [系统消息][9] | 
| apiaccelerometerchange| [重力感应][9] | 
| apicompasschange| [罗盘][9] | 
| apisetnavbartitle| [动态设置导航条文字][10] | 
| apishownavbarloading| [显示导航条加载动画][10] | 
| apihidenavbarloading| [隐藏导航条加载动画][10] | 
| apihidekeyboard| [收起键盘](https://mp.weixin.qq.com/debug/wxadoc/dev/api/ui-other.html) | 
| apinavigateto| [保留当前页面并跳转][11] | 
| apiredirectto| [关闭当前页面并跳转][11] | 
| apinavigateback| [返回上一个页面][11] | 
| apilogin| [登录][19] | 
| apichecksession| [检测session][19] | 
| apigetuserinfo| [用户信息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/open.html) | 
| apipayment| [微信支付](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-pay.html) | 
| apishowtoast| [交互反馈][17] | 
| apihidetoast| [交互反馈][17] | 
| apishowmodal| [交互反馈][17] | 
| apihidemodal| [交互反馈][17] | 
| apishowactionsheet| [交互反馈][17] | 
| getSystemInfoSync| [同步获取系统信息][18] | 
| apiphonecall| [拨打电话][18] | 

[1]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-voice.html "语音"
[2]: https://mp.weixin.qq.com/debug/wxadoc/dev/component/checkbox.html "多选"
[3]: https://mp.weixin.qq.com/debug/wxadoc/dev/component/input.html "文本框"
[4]: https://mp.weixin.qq.com/debug/wxadoc/dev/component/view.html "视图"
[5]: https://mp.weixin.qq.com/debug/wxadoc/dev/component/view.html "单选"
[6]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-background-audio.html "音乐播放控制"
[7]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/data.html "本地数据"
[8]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/location.html  "地理位置"
[9]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/device.html "设备信息"
[10]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/ui.html "导航条动画"
[11]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/ui-navigate.html "跳转"
[12]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-record.html "录音"
[13]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-picture.html "预览选择图片"
[14]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-socket.html "socket"
[15]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-file.html "上传下载文件"
[16]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/file.html "文件"
[17]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-react.html "交互反馈"
[18]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/device.html "设备信息"
[19]: https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-login.html "登录"

### 未添加的 snippet 列表

[动画](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-animation.html).
[绘图](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-canvas.html).
[模板消息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/notice.html).
[同步获取系统信息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/device.html)
[把当前画布的内容导出生成图片](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-canvas.html#wxcanvastotempfilepathobject)
[音频组件控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-audio.html)
[视频组件控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-video.html)

### enjoy && give me a star. ;-D
