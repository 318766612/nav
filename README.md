# twonav

#### 介绍
TwoNav 是一款开源的书签（导航）管理程序，界面简洁，安装简单，使用方便，基础功能免费。TwoNav可帮助你将浏览器书签集中式管理，解决跨设备、跨平台、跨浏览器之间同步和访问困难问题，做到一处部署，随处访问。

当前版本v2.0.39-20230913


#### 安装教程

1. 当前是sqlite数据库，需要修改数据库，删除config.php和data_*.db数据库即可
2. php版本7.3 <= PHP <= 8.1
3. 数据库: SQLite3 或 MySQL > 5.6.0
4. 忘记管理员密码，可以通过ATool工具修改，修改data->ATool_config.php->switch=1,访问http://您的域名/system/ATool.php
5. 若是无法登录，检查服务器文件是否可以读写，修改为777即可

### 功能特色

* 支持后台管理
* 支持私有链接
* 支持加密链接
* 支持分享链接
* 支持二级分类
* 支持用户分组/权限管理
* 支持Chrome/Firefox/Edge书签批量导入
* 支持批量更新链接图标/标题/描述等信息
* 支持链接信息自动识别
* 支持API
* 支持Docker部署
* 支持uTools插件
* 支持Chromium内核的[浏览器扩展]
* 支持简易文章管理
* 支持更换各种模板/支持混搭,20+个主题模板
* 安全性支持:更换登录入口/二级密码/OTP双重验证

![](https://foruda.gitee.com/images/1680680754989095293/fcc56e76_10359480.jpeg "主页预览")
![](https://foruda.gitee.com/images/1680680836189756220/8c227c34_10359480.jpeg "主题模板")

#### 参与贡献

1.  Fork 仓库[https://gitee.com/tznb/TwoNav](https://gitee.com/tznb/TwoNav)

