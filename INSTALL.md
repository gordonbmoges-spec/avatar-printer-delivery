# 安装与下载说明

头像打印机 ZIP安装包 VP-20261103-02

1. 需要电脑，先从Python官网安装Python 3.11或更新版本；直播评论接入还需要Node.js和Chrome。
2. 完整解压。Mac运行1-安装环境.command，再运行2-启动打印机.command。Windows运行1-install-windows.bat，再运行2-start-windows.bat。
3. 若系统不允许双击脚本，在终端进入解压目录，运行python3 launcher.py --install，再运行python3 launcher.py。Windows用python或py -3。不要关闭系统安全保护。
4. 程序会在浏览器打开本机http://127.0.0.1:18081/delivery-start.html；遇端口占用可用python3 launcher.py --port 18082。默认不接直播。
5. 语音使用Edge在线女声，需要联网；初次安装从PyPI下载依赖。软件本身不是离线免依赖exe/dmg，也不含Python/Node安装器。
6. 正式接入：先控制台填自己的直播间，再由自己在独立接收窗扫码；不要关闭直播伴侣。免费评论先验收，礼物不重复花钱测试。
7. 退出先点控制台停止抓取，再在启动终端按Ctrl+C。接收窗口如仍保留可手工关闭，勿关闭所有Chrome。

实际验收范围：Mac本地3D演示、评论及晓晓女声有记录。重复参与修复待实播复验，真实礼物、Windows整套和其他平台待验收。

原项目免费开源：github.com/rhfbgfgfdg999999/3d-printer-live；保留app/LICENSE。服务费对应教程整理与基础配置答疑。

官方依赖下载：

- Python：https://www.python.org/downloads/
- Node.js：https://nodejs.org/en/download
- Chrome：https://www.google.com/chrome/

本包默认是浏览器模式，不需要WebView2或pywebview。客户自行安装依赖、扫码登录；不包含卖家账号、直播间号或浏览器资料。