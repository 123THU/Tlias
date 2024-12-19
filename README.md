# Tlias
学校开设的“诡异”的为期三周周末的企业实践课程(1): Tlias 教学辅助系统项目开发

# Introduction
Tlias系统基于SpringBoot框架完成，由于时间较短，因此仅实现后端的登录认证、员工管理和部门管理部分，前端代码直接给出，基于nginx服务器运行

# Deploy

前端：文件中包含完整的html, css, js代码以及需要的nginx conf的配置文件
  - windows: 直接点击.exe文件即可启动nginx
  - macOS: 自行下载并配置nginx服务器，将前端文件中的conf配置文件设置为自己的nginx服务器的配置文件，即可
        （可参考CSDN文章进行操作：https://blog.csdn.net/weixin_62015493/article/details/136430716）

后端：大部分代码可以直接运行
    注意：1. AliUtilsOSS部分代码需要将OSS的密钥等配置部分更改为自己的OSS的属性，否则会导致上传图片错误
         2. 数据库更改为自己的数据库（原始导入文件见.sql)

前后端都可正常运行之后，浏览器访问http://localhost:90进入登录界面：用户名和密码在数据库的user表中保存，使用哪一个都可以，默认密码为123456


# Interesting Secret:
本repo是我在2024.12.19 中午12:05等午饭的时候闲着无聊create的(doge :) ~
期末周进行中...

     
