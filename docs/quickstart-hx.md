
> `uni-app`支持通过 可视化界面、[`vue-cli`命令行](https://uniapp.dcloud.io/quickstart?id=%e9%80%9a%e8%bf%87vue-cli%e5%91%bd%e4%bb%a4%e8%a1%8c) 两种方式快速创建项目。


可视化的方式比较简单，HBuilderX内置相关环境，开箱即用，无需配置nodejs。

开始之前，开发者需先下载安装如下工具：

- HBuilderX：[官方IDE下载地址](https://www.dcloud.io/hbuilderx.html)

HBuilderX是通用的前端开发工具，但为`uni-app`做了特别强化。

下载App开发版，可开箱即用；如下载标准版，在运行或发行`uni-app`时，会提示安装`uni-app`插件，插件下载完成后方可使用。

如使用`cli`方式创建项目，可直接下载标准版，因为uni-app编译插件被安装到项目下了。


## 创建uni-app

在点击工具栏里的文件 -> 新建 -> 项目：
<div align=center>
  <img src="//img-cdn-qiniu.dcloud.net.cn/uniapp/doc/create1.png"/>
</div>

选择`uni-app`类型，输入工程名，选择模板，点击创建，即可成功创建。

uni-app自带的模板有 Hello uni-app ，是官方的组件和API示例。还有一个重要模板是 uni ui项目模板，日常开发推荐使用该模板，已内置大量常用组件。

<div align=center>
  <img src="//img.cdn.aliyun.dcloud.net.cn/uni-app/doc/create.png"/>
</div>

## 运行uni-app


1. 浏览器运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到浏览器 -> 选择浏览器，即可在浏览器里面体验uni-app 的 H5 版。
  <div align=center>
  	<img src="//img-cdn-qiniu.dcloud.net.cn/uniapp/doc/run-chrome.png"/>
  </div>

2. 真机运行：连接手机，开启USB调试，进入hello-uniapp项目，点击工具栏的运行 -> 真机运行 -> 选择运行的设备，即可在该设备里面体验uni-app。
	<div align=center>
		<img src="//img-cdn-qiniu.dcloud.net.cn/uniapp/doc/run-phone.png"/>
	</div>
	
	如手机无法识别，请点击菜单运行-运行到手机或模拟器-真机运行常见故障排查指南。
	注意目前开发App也需要安装微信开发者工具。
	
3. 在微信开发者工具里运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 微信开发者工具，即可在微信开发者工具里面体验uni-app。
    <br/>
    <div align=center>
    	<img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-1.png"/>
    </div>
    
    **注意：**如果是第一次使用，需要先配置小程序ide的相关路径，才能运行成功。如下图，需在输入框输入微信开发者工具的安装路径。 若HBuilderX不能正常启动微信开发者工具，需要开发者手动启动，然后将uni-app生成小程序工程的路径拷贝到微信开发者工具里面，在HBuilderX里面开发，在微信开发者工具里面就可看到实时的效果。
    
    uni-app默认把项目编译到根目录的unpackage目录。
    <br/>
    <div align=center>
      <img src="//img-cdn-qiniu.dcloud.net.cn/uniapp/doc/weixin-setting.png"/>
    </div>
		
4. 在支付宝小程序开发者工具里运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 支付宝小程序开发者工具，即可在支付宝小程序开发者工具里面体验uni-app。
    <br/>
    <div align=center>
    	<img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-3.png"/>
    </div>

5. 在百度开发者工具里运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 百度开发者工具，即可在百度开发者工具里面体验uni-app。
    <br/>
    <div align=center>
    	<img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-2.png"/>
    </div>
 
6. 在字节跳动开发者工具里运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 字节跳动开发者工具，即可在字节跳动开发者工具里面体验uni-app。
    <br/>
    <div align=center>
    	<img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-4.png"/>
    </div>

7. 在360开发工具中导入：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 360开发工具，即可在360开发工具里面体验uni-app。
    <br/>
    <div align=center>
      <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni-app-debug-mp-360.png"/>
    </div>

8. 在快应用联盟工具里运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 快应用联盟工具，即可在快应用联盟工具里面体验uni-app。
    <br/>
    <div align=center>
      <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni-app-run-debug-quickapp-webview.png"/>
    </div>

9. 在华为开发者工具里运行：进入hello-uniapp项目，点击工具栏的运行 -> 运行到小程序模拟器 -> 华为开发者工具，即可在华为开发者工具里面体验uni-app。
    <br/>
    <div align=center>
      <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni-app-run-debug-quickapp-webview-huawei.png"/>
    </div>

10. 在QQ小程序开发工具里运行：内容同上，不再重复。

**Tips**

* 如果是第一次使用，需要配置开发工具的相关路径。点击工具栏的运行 -> 运行到小程序模拟器 -> 运行设置，配置相应小程序开发者工具的路径。
* 支付宝/百度/字节跳动/360小程序工具，不支持直接指定项目启动并运行。因此开发工具启动后，请将 HBuilderX 控制台中提示的项目路径，在相应小程序开发者工具中打开。
* 如果自动启动小程序开发工具失败，请手动启动小程序开发工具并将 HBuilderX 控制台提示的项目路径，打开项目。

运行的快捷键是`Ctrl+r`。
HBuilderX 还提供了快捷运行菜单，可以按数字快速选择要运行的设备：
<div align=center>
	<img src="//img.cdn.aliyun.dcloud.net.cn/uni-app/doc/runtool.png"/>
</div>

如需调试，可参考：[uni-app调试](/snippet?id=使用-chrome-调试)

## 发布uni-app

### 打包为原生App（云端）

在HBuilderX工具栏，点击发行，选择原生app-云端打包，如下图：

<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-11.png"/>
</div>
出现如下界面，点击打包即可。
<div align=center>
  <img style="max-width:600px;" src="https://vkceyugu.cdn.bspapp.com/VKCEYUGU-dc-site/001a20b0-d85a-11ea-81ea-f115fe74321c.png"/>
</div>

### 打包为原生App（离线）

``uni-app`` 支持离线打包，在 HBuilderX 发行菜单里生成离线打包资源，然后参考离线打包文档操作，可以从HBuilderX的发行菜单里找到文档链接，也可以直接访问：[https://nativesupport.dcloud.net.cn/AppDocs/README](https://nativesupport.dcloud.net.cn/AppDocs/README)。

在HBuilderX工具栏，点击发行，选择本地打包，如下图，点击即可生成离线打包资源。

<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-12.png"/>
</div>

### 发布为H5

1. 在 ``manifest.json`` 的可视化界面，进行如下配置（发行在网站根目录可不配置应用基本路径），此时发行网站路径是 www.xxx.com/h5，如：[https://hellouniapp.dcloud.net.cn](https://hellouniapp.dcloud.net.cn)。
<div align=center>
	<img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/build-h5-1.png" style="max-width:600px;height:auto;"/>
</div>
2. 在HBuilderX工具栏，点击发行，选择网站-H5手机版，如下图，点击即可生成 H5 的相关资源文件，保存于 unpackage 目录。

<div align=center>
	<img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-10.png" style="max-width:600px;height:auto;"/>
</div>

**注意**
- `history` 模式发行需要后台配置支持，详见：[history 模式的后端配置](https://router.vuejs.org/zh/guide/essentials/history-mode.html#%E5%90%8E%E7%AB%AF%E9%85%8D%E7%BD%AE%E4%BE%8B%E5%AD%90)
- 打包部署后，在服务器上开启 gzip 可以进一步压缩文件。具体的配置，可以参考网上的分享：https://juejin.im/post/5af003286fb9a07aac24611b

### 发布为小程序

**发布为微信小程序：**
1. 申请微信小程序AppID，参考：[微信教程](https://developers.weixin.qq.com/miniprogram/dev/#申请帐号)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "小程序-微信"，输入小程序名称和appid点击发行即可在 ``unpackage/dist/build/mp-weixin`` 生成微信小程序项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-6.png"/>
</div>
3. 在微信小程序开发者工具中，导入生成的微信小程序项目，测试项目代码运行正常后，点击“上传”按钮，之后按照 “提交审核” => “发布” 小程序标准流程，逐步操作即可，详细查看：[微信官方教程](https://developers.weixin.qq.com/miniprogram/dev/quickstart/basic/release.html)。

**发布为百度小程序：**
1. 入驻小程序并申请百度小程序AppID，参考：[百度小程序教程](https://smartprogram.baidu.com/docs/introduction/enter_application/)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "小程序-百度"，输入小程序名称和appid点击发行即可在 ``/unpackage/dist/build/mp-baidu`` 生成百度小程序项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-7.png"/>
</div>
3. 在百度小程序开发者工具中，导入生成的百度小程序项目，测试项目代码运行正常后，点击“上传”按钮上传代码，之后在百度小程序的 [管理中心](https://smartprogram.baidu.com/developer/applist.html) 选择创建的应用点击前往发布，选择对应的版本然后提交审核。


**发布为支付宝小程序：**
1. 入驻支付宝小程序，参考：[支付宝小程序教程](https://docs.alipay.com/mini/introduce)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "小程序-支付宝"，即可在 ``/unpackage/dist/build/mp-alipay`` 生成支付宝小程序项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-8.png"/>
</div>
3. 在支付宝小程序开发者工具中，导入生成的支付宝小程序项目，测试项目代码运行正常后，点击“上传”按钮上传代码，在 [支付宝小程序后台](https://open.alipay.com/platform/mini.htm#/app)，选择刚提交的版本点击提交审核，详见：[支付宝小程序文档](https://docs.alipay.com/mini/developer/publish)。


**发布为字节跳动小程序：**
1. 入驻字节跳动小程序，参考：[字节跳动小程序教程](https://developer.toutiao.com/dev/cn/mini-app/introduction/plug-in/registration)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "小程序-字节跳动"，即可在 ``/unpackage/dist/build/mp-alipay`` 生成字节跳动小程序项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni20190222-8.png"/>
</div>
3. 在字节跳动小程序开发者工具中，导入生成的字节跳动小程序项目，测试项目代码运行正常后，点击“上传”按钮上传代码，在 [字节跳动小程序后台](https://developer.toutiao.com/app/applist)，选择刚提交的版本点击提交审核，详见：[字节跳动小程序文档](https://developer.toutiao.com/dev/cn/mini-app/introduction/plug-in/verification)。

**发布为360小程序：**
1. 入驻360小程序，参考：[360小程序教程](https://mp.360.cn/doc/miniprogram/dev/#/)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "小程序-360"，即可在 ``/unpackage/dist/build/mp-360`` 生成360小程序项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni-app-release-mp-360.png"/>
</div>
3. 在360浏览器中，导入生成的360小程序项目

**注意**
- 目前仅windows平台支持。360浏览器自身不支持mac平台。


**发布为快应用(webview)：**
1. 入驻快应用(webview)，参考：[快应用(webview)教程](https://www.quickapp.cn/)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "快应用联盟"，即可在 ``/unpackage/dist/build/quickapp-webview`` 生成快应用(webview)项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni-app-run-release-quickapp-webview.png"/>
</div>
3. 在快应用联盟工具中，导入生成的快应用联盟项目，测试项目代码运行正常后，点击”构建“打包正式版，在[快应用联盟后台](https://www.quickapp.cn/)上传


**发布为快应用(webview) - 华为：**
1. 入驻华为快应用，参考：[华为快应用教程](https://developer.huawei.com/consumer/cn/quickApp)。
2. 在HBuilderX中顶部菜单依次点击 "发行" => "快应用-华为"，即可在 ``/unpackage/dist/build/quickapp-webview`` 生成华为快应用项目代码。
<div align=center>
  <img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/doc/uni-app-run-release-quickapp-webview-huawei.png"/>
</div>
3. 在华为开发者工具中，导入生成的华为快应用项目，测试项目代码运行正常后，点击”构建“打包正式版，在[华为快应用后台](https://developer.huawei.com/consumer/cn/quickApp)上传


**发布为QQ小程序：**
内容同上，不再重复。

发布的快捷键是`Ctrl+u`。同样可拉下快速发布菜单并按数字键选择。
