# capturesqli
利用流量工具，抓取流量层面的sql注入、高危命令等等攻击

编写抓包的代码，编译然后运行：
我设置的是抓所有端口的包：

![图片](https://github.com/user-attachments/assets/44e39b21-e97b-4f06-92f9-d004838ffb16)


4、开始测试：

![图片](https://github.com/user-attachments/assets/a0e3b42b-1e19-474c-9c3a-f279b5e167d5)


输入正常的用户名和密码，抓包程序过滤掉了。
分别输入union 和 or 1=1 等sql注入的密码进行测试（注意：目前这个版本没检测混淆或绕过的sql注入）
发现告警了：

![图片](https://github.com/user-attachments/assets/997dfb0a-7458-47b5-a1da-7bfb0596ef22)

 
对于告警信息，我们还可以发送到钉钉上。

![图片](https://github.com/user-attachments/assets/b67c9ea0-9909-46a0-a0f2-109273293e85)



