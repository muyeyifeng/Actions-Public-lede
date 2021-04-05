#ACTIONS

针对x86-64, rpi2-32bit, rpi3-64bit, rpi4-64bit 四种平台定时编译。

Artifacts内容包括：

    各平台的镜像合集（targets文件夹）；
    
    编译出的插件合集（packages文件夹）；
    
    各平台单一镜像（img.gz）
    
    x86-64平台vmdk文件

同时构建docker镜像：

其中aarch64, rpi364, rpi464在arm64机器上通用，只是所选插件略有不同

阿里云镜像地址：

    git pull registry.cn-beijing.aliyuncs.com/muyeyifeng/lede-x64

    git pull registry.cn-beijing.aliyuncs.com/muyeyifeng/lede-rpi364

    git pull registry.cn-beijing.aliyuncs.com/muyeyifeng/lede-rpi2-3-4

    git pull registry.cn-beijing.aliyuncs.com/muyeyifeng/lede-aarch64

    git pull registry.cn-beijing.aliyuncs.com/muyeyifeng/lede-rpi464

Docker Hub 镜像地址:

    git pull muyeyifeng/lede-x64

    git pull muyeyifeng/lede-rpi364

    git pull muyeyifeng/lede-rpi2-3-4

    git pull muyeyifeng/lede-aarch64

    git pull muyeyifeng/lede-rpi464
