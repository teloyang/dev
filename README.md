###yii2.0 安装步骤

- 在 Windows 中，你首先需要下载并运行 Composer-Setup.exe


输入Composer 命令验证安装是否成功


- Composer 安装后，切换到一个可通过 Web 访问的目录，执行如下命令即可安装 Yii ：

 通过windows的'cmd'命令进入dos命令窗口，执行如下命令

composer global require "fxp/composer-asset-plugin:~1.1.1"


composer create-project --prefer-dist yiisoft/yii2-app-basic yiitest



- 如果你想安装 Yii 的最新开发版本，可以使用以下命令代替， 它添加了一个 stability 选项（中文版）:

composer create-project --prefer-dist --stability=dev yiisoft/yii2-app-advanced  yiitest

等待时间比较长



- 初始化


先进入你的安装的项目目录

执行 init 命令




- 验证

http://localhost/yii2test/frontend/web/index.php