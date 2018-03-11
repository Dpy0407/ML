# ML相关环境搭建说明
* ## pip源修改为国内镜像
**临时使用**
> pip install -i https://pypi.tuna.tsinghua.edu.cn/simple some-package

**全局设置**
pip 和 pip3 并存时，只需修改 ~/.pip/pip.conf(没有就创建一个)
> [global]
index-url = https://pypi.tuna.tsinghua.edu.cn/simple

* ## 需要安装的库：
matplotlib numpy pandas scipy pillow sklearn
其中，安装matplotlib包含了numpy
> sudo pip3 install matplotlib pandas scipy pillow sklearn


