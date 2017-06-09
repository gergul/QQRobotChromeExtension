# QQRobotChromeExtension
A QQ robot chrome extension

基于web qq使用了一种比较简单的方式实现了QQ机器人，过程中没有使用复杂的web接口，仅仅使用了html dom操作实现的。


特色：

  1、不使用复杂的webqq接口，避免腾讯更改了接口就不能使用的尴尬；
  
  2、纯粹的html dom操作让一切一目了然；
  
  3、部署简单，只需一个浏览器（支持chrome插件的浏览器）就可以超快速部署。


安装：

  1、打开chrome的“扩展程序”中的“开发者模式”；
  
  2、“加载已解压的扩展程序...”，选择“QQRobot”文件夹；
  
  3、打开“w.qq.com”，使用手机扫码登录即可。
  
  
自动问答机器人快速部署：

  1、图灵机器人部署
  
     到www.tuling123.com 上申请一个你的机器人，创建机器人后会得到你的ApiKey，把这个ApiKey复制到myMessageHandle.js中对应的位置，重新载入插件即可生效。
     
  2、茉莉机器人部署
  
     茉莉机器人我使用了公共的API，所以不需要任何配置就可以使用了。


机器人命令：

  发送：robot:help 消息给机器人就可以查询所有命令。


注意：

登录Web QQ后，有时候会出现会话列表为空的情况，这可能是Web QQ的一个bug，这种情况下是不能收发到QQ消息的，我遇到这种情况后，也没能找到解决办法，后来隔天登录，会话列表又回来了，又好了。


本QQRobotChromeExtension开源项目交流QQ群：13225803
