# Piwik安装
## 运行Piwik所需的配置
> * Web服务器,如Apache,nginx,IIS等
* PHP版本5.5.9或更高
* MySQL版本5.5或更高，或MariaDB
* （默认启用）PHP扩展pdo和pdo_mysql，或mysqli扩展。

## 开始安装
>1. 下载最新版本的Piwik [点击下载](https://builds.piwik.org/piwik.zip)
2. 将zip文件解压到硬盘的文件夹中.这将创建一个包含文件和目录的"Piwik"文件夹
3. 打开你的FTP客户端,并将Piwik文件以二级制模式上传到你的Web服务器上的所需要的位置.所有文件都可以上传到公共www文件夹中的“analytics”子目录，例如 http://yourdomain.org/analytics/  或者您可以在自己的子域中设置Piwik，并上传所有的文件到 http://analytics.example.org/

### 安装
> 打开您的网络浏览器并导航至您上传Piwik的网址。如果一切正常上传，您应该看到Piwik安装欢迎屏幕。如果有任何问题，Piwik将识别他们并帮助您解决问题。

1. 开始点击安装的时间了！点击下一步!
![alt text](https://piwik.org/wp-content/uploads/2008/11/1-welcome1-700x389.png)

2. Piwik将检查以确保您的服务器符合Piwik要求。如果一切正常，你会看到一个像这样的长列表：
![alt text](https://piwik.org/wp-content/uploads/2008/11/2a-check-success1-700x332.png)

3. 设置mysql数据库相关信息,mysql用户需要有创建,添加,查询数据库的权限:
![alt text](https://piwik.org/wp-content/uploads/2008/11/3-database1.png)

4. Piwik会将必要的表格添加到您的数据库中：
![alt text](https://piwik.org/wp-content/uploads/2008/11/4-created1-700x371.png)

5. 超级用户是您在安装Piwik时创建的用户。此用户拥有最高的权限。选择您的用户名和密码：
![alt text](https://piwik.org/wp-content/uploads/2008/11/5-general-setup1-700x338.png)
`每个piwik只有一个超级用户,这是您第一次登录piwik唯一方法`

6. 输入您要跟踪的第一个网站的名称和网址。安装完成后，您可以添加更多的网站。
![alt text](https://piwik.org/wp-content/uploads/2008/11/6-setup-website1.png)

7. Piwik会给你一个JavaScript标签。此代码必须出现在您希望Piwik分析的每个页面上。我们建议您在结束</head>标记（或所有页面顶部包含的常规标题文件）之前立即粘贴此代码。
![alt text](https://piwik.org/wp-content/uploads/2008/11/7-javascript-tag1-700x378.png)

8. 安装成功
![alt text](https://piwik.org/wp-content/uploads/2008/11/8-congrats1-700x373.png)





