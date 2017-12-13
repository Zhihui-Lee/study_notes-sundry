# Piwik追踪
### 添加新的客户端应用分析
> 当你需要添加新的客户端分析,需要在piwik管理中配置

1. 点击右上角的管理,进入网站管理页面
![](https://raw.githubusercontent.com/hui348950395/gitbook_img/master/notes_img1.png)

1. 点击添加网站填写相关的信息,根据自己的需求来填写.
![](https://github.com/hui348950395/gitbook_img/raw/master/20171213/img1.png)

2. 点击保存后会生成每个客户端应用的id,这个id是用来追踪应用时,客户端需要根据你`piwik的url和id`
![](https://github.com/hui348950395/gitbook_img/raw/master/20171213/2.png)

3. 接下来就是统计应用访问了,官方是推荐使用JavaScript的方式的.在管理网站页面每个应用下都有显示跟踪代码的选项,点击进入会看到一段JavaScript 跟踪代码,这是自动生成的.
![](https://github.com/hui348950395/gitbook_img/raw/master/20171213/3.png)

4. 把这段代码放到你需要追踪的网页 </head> tag标签里,这就算简单的完成了,会追踪你网页的访问量,跳出率等等数据,需要其他扩展的分析可以仔细研究[官方文档](https://piwik.org/docs)

`ps:`如果是移动端的请[点击下载安卓SDK](https://github.com/piwik/piwik-sdk-android)和[点击下载IOS SDK](https://github.com/piwik/piwik-sdk-ios),根据SDK的文档整合到应用中.
