# 由于pushplus强制实名所以此仓库吧原仓库的推送改成了Server酱


# 原仓库👇
https://github.com/komori-flag/glados_automation
在此基础上删掉了青龙面板和自动同步上游代码


# glados自动签到，实现无限白嫖。

环境变量：`GLADOS_COOKIE`（必要） 和 `SERVERCHAN`（非必要）

 `GLADOS_COOKIE`多个账号需使用 '&' 隔开
  示例：cookie&cookie&cookie



# 食用方法 （github_actions）

 1.点击右上角 **fork** 按钮 
 
 2.在自己仓库中打开此项目
 
 3.配置环境变量：
   打开 GLaDOS 签到页面
   打开浏览器「开发者工具」(快捷键 F12 或 Ctrl+Shift+I), 切换到「网络 Network」标签页
   找到名字为 status 这一行, 点击打开详情, 在「请求头 Request」找到 Cookie, 格式类似 koa:sess=xxxxxx; koa:sess.sig=xxxxxx, 复制出来

 
 4.点亮右上角的星星 **star** 激活 actions
 
 5.然后点击 Actions 标签查看运行的详细状况

