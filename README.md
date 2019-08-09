# 郑爽鼓励师

在 VS Code 中连续写代码一小时（时间可配置），会有郑爽提醒你该休息啦~

## 使用

除了每过一小时会自动弹出提醒页面，也可以按 `F1`, 然后输入 `zs: 打开提醒页面`来打开提醒页面


## 配置

* `zs.reminderViewIntervalInMinutes`: 展示提醒页面的时间间隔（分钟）。(默认值为**60**)，插件右键点击**配置扩展设置**可以进行更改
* `zs.title`: 提示文字。 (默认值为**大兄弟，歇会儿吧，还想不想要你的头发了~**)
* `zs.type`: default (默认图)；url (图片地址)。(默认值为**default**)
* `zs.customImages`: 配置图片数组（需要搭配zs.type为url） (默认值为**默认图片**)

```
如下例子，使用自定义图片：
"zs.type": "url",
"zs.customImages": [
    "http://n.sinaimg.cn/sinacn13/480/w1280h800/20180418/f6d9-fzihnep4066297.jpg"
]
```
## 如何使用本地图片作为展示图片

* vscode不允许读取外部文件路径，所以只能自己去替换插件内的图片。替换步骤如下：
  
  1、找到vscode插件安装的地方 (如mac 在~/.vscode/extensions/yyshengfan.zs-{version})
  
  2、替换images/zhengshuang内图片
