########
安装说明
########

此软件基于 Python 3.3 编写，不支持 Python 2.X，仅依赖标准库。

安装依赖
========

Linux/Mac
---------

图形界面使用了 tkinter 库，虽然这个库是标准库的一部分，但是某些发行版可能分离出来独立打包，而默认不随 python 包安装，所以要手动安装。

Windows
-------

打开 http://www.python.org/download/ 需要版本是 3.3.x，编写此文档时最新版本是 3.3.3。

* 32 位系统下载 Python 3.3.3 Windows x86 MSI Installer 这个文件

* 64 位系统下载 Python 3.3.3 Windows X86-64 MSI Installer 这个文件。

双击运行安装包，安装到随便一个目录即可，安装后默认自动关联 .py 和 .pyw 文件，无需特别配置。

运行
====

执行文件只有程序根目录下的 niconvert.pyw，会自动根据当前环境判断使用命令行还是图形界面。

* 如果双击打开，则使用图形界面。

* 如果在终端调用，则使用命令行界面，可用 ``niconvert.pyw -h`` 获取使用帮助。

* 如果在终端以 ``niconvert.pyw tk`` 参数调用，则使用图形界面。

卸载和更新
==========

所谓的绿色软件，卸载就是直接删掉程序根目录即可，更新就是重新下载覆盖根目录。

小软件就不特别弄版本号了，每次打包下载主干仓库就是最新版本，每次提交就是更新日志。
