# wechat-applets-sublime-plug微信小程序敏捷开发sublime插件
----
###后续有时间延续上一作者持续进行更新

###简介

本人从零开始进行开发小程序，为了快速开发小程序引用sublime插件进行敏捷响应项目开发，找到了一个还算比较靠谱的开发插件，但是作者在2016年的时候停止更新维护了，本人项目空闲时间会持续维护该插件，方便广大人使用，有兴趣的也可以进行更改，修正，感谢！

### 安装部署

将下载好的代码片段放入 Sublime text安装目录/Packages/User 目录中即可.

然后重新启动sublime,把wxml格式设置为html否则sublime无法识别为html代码

### snippet 列表

为了防止和其他 snippet 冲突,本 snippet 中的所有WXML 标签触发命令都以'w'开头,所有 API>    相关命令都以'api'开头.

#### WXML snippet

| 命令 | 对应组件或命令 |
| -----|----:|
| wapp | [注册小程序](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/app.html) |
| wblockif | [block wx:if](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/conditional.html)  |
| wbutton | [button](https://mp.weixin.qq.com/debug/wxadoc/dev/component/button.html) |
| wcheckbox | [checkbox][2] |
| wcheckboxgroup | [checkbox-group][2] |
| ~~wactionsheet~~ | [~~action-sheet~~](https://mp.weixin.qq.com/debug/wxadoc/dev/component/action-sheet.html) |
| wcanvas | [canvas](https://mp.weixin.qq.com/debug/wxadoc/dev/component/canvas.html#canvas) |
| wimage |[image](https://mp.weixin.qq.com/debug/wxadoc/dev/component/image.html)|
| wtext | [text](https://mp.weixin.qq.com/debug/wxadoc/dev/component/text.html) |
| wview | [view][4] |
| wviewbind | [view 事件](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/event.html) |
| wmap | [map](https://mp.weixin.qq.com/debug/wxadoc/dev/component/map.html)|
| ~~wmodal~~ | [~~modal~~](https://mp.weixin.qq.com/debug/wxadoc/dev/component/modal.html)|
| wnavigator |[navigator](https://mp.weixin.qq.com/debug/wxadoc/dev/component/navigator.html)|
| wexport | [模块化](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/module.html)|
| wfor | [for](https://mp.weixin.qq.com/debug/wxadoc/dev/view/wxml/data.html) |
| wform |[form](https://mp.weixin.qq.com/debug/wxadoc/dev/component/form.html)|
| wradio|[radio][5]|
| wradiogroup|[radio-group][5]|
| wslider|[slider](https://mp.weixin.qq.com/debug/wxadoc/dev/component/slider.html)|
| wicon|[icon](https://mp.weixin.qq.com/debug/wxadoc/dev/component/icon.html)|
| winput|[input][3]|
| wtextarea|[textarea](https://mp.weixin.qq.com/debug/wxadoc/dev/component/textarea.html)|
| winfutautofocus|[input][3]|
| ~~wtoast~~|[~~toast~~](https://mp.weixin.qq.com/debug/wxadoc/dev/component/toast.html)|
| wvideo|[video](https://mp.weixin.qq.com/debug/wxadoc/dev/component/video.html)|
| winputfocus|[input][3]|
| wlabel|[label](https://mp.weixin.qq.com/debug/wxadoc/dev/component/label.html)|
| ~~wloading~~|[~~loading~~](https://mp.weixin.qq.com/debug/wxadoc/dev/component/loading.html)|
| wpage|[Page()](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/page.html)|
| wprogress|[progress](https://mp.weixin.qq.com/debug/wxadoc/dev/component/progress.html)|
| wscrollview|[scroll-view](https://mp.weixin.qq.com/debug/wxadoc/dev/component/scroll-view.html)|
| wswitch|[switch](https://mp.weixin.qq.com/debug/wxadoc/dev/component/switch.html)|
| wtemplate|[template](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/template.html)|
| wswiper|[swiper](https://mp.weixin.qq.com/debug/wxadoc/dev/component/swiper.html)|
| wviewelif|[view][4]|
| wviewelse|[view][4]|
| wviewif|[view][4]|

### 小程序API snippet

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
