> 前言：在上一家公司的时候开发过两个小程序，上线了快一年多了，离职后就很少接触了，一直说要抽时间总结下小程序前端开发的一些注意点，今天终于可以开始了，hhhh。

## 1. 下载资源

- **登录网站 [阿里巴巴字体图标](http://www.iconfont.cn/) **

![Aaron Swartz](https://upload-images.jianshu.io/upload_images/9028759-eb49958739402c14.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **新建项目**

![Aaron Swartz](https://upload-images.jianshu.io/upload_images/9028759-64e788bf6a2035da.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


- **添加和下载**

![Aaron Swartz](https://upload-images.jianshu.io/upload_images/9028759-92a6a041c45be935.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![Aaron Swartz](https://upload-images.jianshu.io/upload_images/9028759-02b91f47d0386407.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

-------------------

## 2. 微信小程序中使用

- **将修改后的iconfont.css里面的代码全部复制到微信小程序中需要用到的wxss文件中，我的如下： (注意：src这里经过了base64加密处理)**


![Aaron Swartz](https://raw.githubusercontent.com/linshengqi/MarkdownPhotos/master/font.wcxss_1.png)

![Aaron Swartz](https://raw.githubusercontent.com/linshengqi/MarkdownPhotos/master/font.wxss.png)


- **app.wxss全局引用**
![Aaron Swartz](https://raw.githubusercontent.com/linshengqi/MarkdownPhotos/master/app.wxss.png)


- **wxml中引用**
![Aaron Swartz](https://raw.githubusercontent.com/linshengqi/MarkdownPhotos/master/index.wxml.png)


- **效果图**
![Aaron Swartz](https://raw.githubusercontent.com/linshengqi/MarkdownPhotos/master/indexPage.png)


