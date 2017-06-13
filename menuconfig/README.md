# 说明：

linux内核配置的命令：

```
make config
make xconf
make menuconfig
```

其中，make menuconfig 叫人的感觉是又方便，又美观，因此，本工程的目的就是将内核中的相关部分抽离出来。
linux内核版本：

> linux-4.1.18

# 功能：

- 为配置提供可视化的图形界面
- 自动生成 #define 宏
- 更改方便

# 示例：

![输入图片说明](http://git.oschina.net/uploads/images/2016/0311/102732_14b3960b_556919.png "make menuconfig 图形界面")

# 演示的方法：

**1.将工程下载到本地：**

```
git clone http://git.oschina.net/qqliyunpeng/menuconfig
```

**2.这里是列表文本2. 进入 menuconfig 目录执行**

```
make menuconfig
```

**3.将界面中的 led's states 选中，退出界面**

```
make
./test
```

# 实际应用的方法：

> 未完成。。
>

# 说明：

1. make menuconfig 命令解析的是 Kconfig 文件，如果你不知道应该如何写一个 Kconfig 文件，可以传看 [kconfig-language.txt](http://git.oschina.net/qqliyunpeng/menuconfig/blob/master/kconfig-language.txt?dir=0&filepath=kconfig-language.txt&oid=350f733bf2c7165fd13a960df68bbfebf4a34bf8&sha=b39d4b87e247e2b7c8a450a89afda27642374710)

2. 对里边的bool类型的宏，在使用的时候要用 #ifdef ，不能使用 if(宏的值 == 1) 

# 项目参与人员：

- qqliyunpeng
- zhangyla