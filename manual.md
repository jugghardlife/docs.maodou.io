# 毛豆网用户手册
## 1. 网站用户手册

### 1.1 用户注册与登陆

在创建项目前，我们需要到网站[注册页面](https://maodouapp.com/register)注册一个新用户，老用户请到[登陆页面](https://maodouapp.com/login)直接登陆。如下图所示：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/user-reg.png)

注册成功后，我们会发送一封邮件到您的邮箱账户，请您打开邮件内的链接地址，对邮箱进行验证，验证成功后，即可自动登陆。

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/email-varify.png)

以后即可使用您的邮箱和密码来登陆本网站。

### 1.2 创建一个网站应用

在[网站首页](https://maodouapp.com/)，点击*立即体验*按钮，就会进入到我们的实例列表页面，这里显示着我们创建的网站列表。如下图所示，目前我们还没有创建任何网站，赶快点击按钮或者点击上面的*新建*按钮，来创建我们的第一个网站吧！

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/new-app-page.png)

点击按钮后，可以看到创建一个网站的流程共分为三步：

1. 板块与功能： 选择网站需要的模板和功能2. 网站信息： 填写网站的名称和二级域名的名字3. 网站部署： 一键部署网站到我们的云端

下面以图例说明整个流程：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-muban.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-info.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-deploy.png)

恭喜，通过简单的三步，我们已经生成了一个初备功能的网站应用。

我们还可以点击*Apps*按钮，来查看已创建的网站应用列表：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-instance.png)

下图为这个网站的基本布局和内容，可以看到有*新闻*、*活动*、*管理员后台*等功能，其中新闻、活动页面默认添加了一些内容，大家可以点击浏览一下：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-final.png)

### 1.3 网站应用的简单配置

我们还可以更改网站的样式，如文章中图片和菜单的显示位置，以及菜单的颜色等等。具体操作如下：

点击*管理员后台*按钮，进入后台设置：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-admin.png)

点击分类按钮，可以看到文章设置的各种功能，这里我们更改图片的位置：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-post.png)

更改前，图片默认显示在左边：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-pic-left.png)

更改后，可以看到图片已经位于右边：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-pic-right.png)

其他功能如添加新文章、新活动，大家可以自行体验，我们也会陆续地加入更多的功能。

### 4.微信登录配置

接下来，让我们的网站集成微信登录的功能，首先登录您的[微信公众号](https://mp.weixin.qq.com/)，点击**开发**下的**基本配置**按钮，就可以看到您的微信公众号的应用ID和应用密钥，如下图：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-secret.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-app-secret.png)

接下来，我们需要配置微信登录的回调页面地址，点击**开发**下的**接口权限**按钮，下翻到**网页授权**一栏，点击**网页授权获取用户基本信息**中的修改按钮，进入到功能设置，点击下面的网页授权域名一栏的设置按钮，就能设置回调地址了，如下图：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-api-inter.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-app-web.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-app-url-set.png)

如果您还没有微信公众号，请到[微信公众号注册页面](https://mp.weixin.qq.com/cgi-bin/readtemplate?t=register/step1_tmpl&lang=zh_CN)按照其流程进行注册．

您还可以通过申请一个[微信测试号](http://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/login)来进行体验和测试，登录成功后，就能直接看到微信测试号的应用ID和应用密钥，同样，我们需要配置登录后的回调页面，下翻到**网页账号**一栏，修改**网页授权获取用户基本信息**中的回调地址，如下图：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-app-secret-test.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-app-test-web.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-app-web-url.png)

通过以上步骤，就能获取微信公众号的应用ID和应用密钥，以供下面使用：

回到我们的应用首页，点击*管理员后台*按钮，进入后台的微信设置，填写您的微信公众号的应用ID和应用密钥，并提交：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/app-wx.png)

然后返回我们的首页，点击**微信一键登录**按钮，就会进入微信的授权确认页面，点击确定后，我们就完成了微信登录这一功能：

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-login.png)

![](https://of6ygwuso.qnssl.com/wiki/web-user-docs-pic/wx-final.png)