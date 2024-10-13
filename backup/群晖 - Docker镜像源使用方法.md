### 群晖设置
**使用电脑在浏览器打开群晖的控制面板，选择套检中心，按一下操作打开，Container Manager**
![套件中心](https://tc.xinju.eu/lc/2024/10/02/66fc55212f206.webp)
**按照以下操作设置注册表**
![注册表](https://tc.xinju.eu/lc/2024/10/02/66fc56872592d.webp)
**点击新增**
![新增](https://tc.xinju.eu/lc/2024/10/02/66fc587b4d991.webp)
**设置注册表名称以及注册表URL，用户名及密码留空，最后点击应用**

**注册表地址，请联系网站管理员获取**

**可用注册表：https://fsu.hub.xinju.eu**
![注册表地址](https://tc.xinju.eu/lc/2024/10/02/66fc598c6b917.webp)
**然后返回选择刚刚新建的注册表，点击使用，然后关闭窗口**
![使用](https://tc.xinju.eu/lc/2024/10/02/66fc5c4fcbb91.webp)

### 下载镜像
**方法一**
**在Container Manager中，选择注册表，并在右上角点击搜索，搜索自己需要的镜像，如果有，则可以将镜像下载到本地进行使用，如果没有，请参照方法2**
![下载镜像](https://tc.xinju.eu/lc/2024/10/03/66fe81feca272.webp)
**方法二**
**在Container Manager中，点击映像，依次点击操作，选择导入从URL添加**
![从URL添加](https://tc.xinju.eu/lc/2024/10/03/66fe82df97f24.webp)
**在这个界面中，我们需要添加镜像的地址，进行下载，镜像的地址需要按照下面的操作进行获取**
![获取](https://tc.xinju.eu/lc/2024/10/03/66fe835245256.webp)
**在浏览器中，我们需要打开这个网页，https://hub.docker.com/，由于国内网络不稳定的原因，请大家自备魔法上网**

**按照图片所示，搜索你需要的镜像名称，图片中是以Alist举例，输入你需要的镜像名称后回车即可**
![https://hub.docker.com/](https://tc.xinju.eu/lc/2024/10/03/66fe84f9825ce.webp)
**然后找到你需要的镜像地址，点击进去，图片以Alist举例**
![Alist举例](https://tc.xinju.eu/lc/2024/10/03/66fe85a00c660.webp)
**进入过后，在项目地址的左上方或者右下方的Docker Pull中复制项目地址，项目地址一般都是以xxx/xxx的形式表现**
![Docker Pull中复制项目地址](https://tc.xinju.eu/lc/2024/10/03/66fe86314720f.webp)
**得到项目地址过后，用镜像源和项目地址拼接下载镜像，以文档中提到的镜像地址举例**

**拼接过后的下载地址：https://fsu.hub.xinju.eu/xhofe/alist**

**其中xhofe/alist就是https://hub.docker.com中Alist的项目地址，https://fsu.hub.xinju.eu/就是镜像源地址**

**然后回到Container Manager中，将拼接过后的地址，填入Hub 页面或存储库 URL中，在点击导入**
![](https://tc.xinju.eu/lc/2024/10/03/66fe835245256.webp)

<!-- ##{"script":"<script src='https://blog.meekdai.com/Gmeek/plugins/GmeekTOC.js'></script>"}## -->


