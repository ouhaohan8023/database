使用须知
===============
不要问我为什么把这个东西传到Github来，因为我上不了百度云。。。
TMD
* 将后缀为.ohh的文件改成.exe的执行文件
* 解压.7z文件获得破解补丁
* 终端进入破解补丁根目录 执行

`Patch.exe <navicate.exe path>`

其中<navicate.exe path>为navicate.exe的绝对路径，且需要加引号，例如：

`Patch.exe "D:\Navicat Premium 12\navicat.exe"`

此时会在破解补丁根目录下生成`RegPrivateKey.pem`

继续执行

`Keygen.exe RegPrivateKey.pem`

根据提示任意输入用户名和密码

再终端上会看到注册码，这个时候可以断网了，断网了，断网了

同时，不要敲回车了，终端会要求你输入请求码

打开刚装好的navicate.exe，输入激活码，点击激活

由于断网了，会提示无法链接服务器，这个时候选择`手动激活`，复制跳出来的请求码，粘贴到终端，回车，回车

正常情况下，终端会返回激活码，复制到navicate的框中，点击激活

激活成功。


PS.

如果在执行`Patch.exe <navicat.exe path>`命令时出现报错，`由于找不到MSVCR120.dll，无法继续执行代码。重新安装程序可能会解决此问题。`需要安装Microsoft Visual C++ 2013 Redistributable x86和x64：

同理，将对应文件的.ohh后缀换成.exe，双击安装即可使用