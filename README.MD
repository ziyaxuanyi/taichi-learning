# taichi教程学习
## 1.taichi安装
终端
```shell
pip install taichi
```

在wsl2中可能会找不到cuda路径，需要在环境变量中增加一下cuda路径
终端
```shell
sudo vim ~/.bashrc
```
在最末尾添加
export LD_LIBRARY_PATH=/usr/lib/wsl/lib:$LD_LIBRARY_PATH
然后在终端
```shell
sudo source ~/.bashrc
```

注意在wsl2中要运行示例，必须要有图形支持，wsl2已经可以更新到wslg，即可支持图形显示
只需在powershell中执行更新，然后重启wsl即可
```shell
wsl --update
wsl -shutdown
```