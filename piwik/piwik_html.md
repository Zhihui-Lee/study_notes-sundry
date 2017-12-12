# 将Piwik报告嵌入HTML页面
> Piwik可以是在其他网站嵌入Piwik报告,您只需要将一行代码复制并粘贴到任何可以使用iframe标记的上下文中。

### 更改用户权限
首先，你必须配置权限。默认情况下，Piwik不会让其他人看到您的数据。您可以通过以下两种方式之一公开数据：


* Piwik的用户管理部分设置匿名用户的查看权限
* 将Piwik小部件嵌入到受密码保护的页面或专用页面上
* 从“管理用户”页面复制此用户的`“token_auth”`，并将其粘贴到Widget嵌入HTML代码中的Widget URL的末尾：
```
＆token_auth = your_token_auth_here
```

### 将Piwik报告嵌入HTML页面
在piwik页面右上角点击管理,进入`小工具`菜单,最下方所有的小部件都列出了实时预览,下面有html代码.

![alt text](https://piwik.org/wp-content/uploads/2011/01/iframe_chose-700x340.png)

然后你可以直接整合到需要嵌入的页面

![alt text](https://piwik.org/wp-content/uploads/2011/01/wp_iframe_display-700x506.png)

### 自定义小部件
要自定义小部件日期，网站ID或初始视图（表格，图表，表格显示目标指标），您可以在嵌入代码中编辑URL中的参数：

* idSite - 网站ID
* period - 周期(一天,一周,一个月或者一年)
* date - 日期(YYYY-MM-DD),日期范围（YYYY-MM-DD，YYYY-MM-DD）
* disableLink - 通常设置为1; 启用后，点击进化图将页面重定向到Piwik仪表板
* viewDataTable - 定义窗口小部件“视图”，并可以有以下值：


1. `tableAllColumns`
1. `tableGoa`
1. `table`
1. `cloud`
1. `graphPie`
1. `graphVerticalBar`
1. `graphEvolution`

例如，要将小部件数据默认显示为条形图，可以在小部件URL中进行设置
```
&viewDataTable=graphVerticalBar
```


