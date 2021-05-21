# MobaXterm Keygen

## How it work?

Please see source code. It is not complex.

## How to use?

```
Usage:
    MobaXterm-Keygen.py <UserName> <Version>

    <UserName>:      The Name licensed to
    <Version>:       The Version of MobaXterm
                     Example:    10.9
```

EXAMPLE:

```
PS C:\Users\DoubleSine\Github\MobaXterm-Keygen> .\MobaXterm-Keygen.py "DoubleSine" 10.9
[*] Success!
[*] File generated: C:\Users\DoubleSine\Github\MobaXterm-Keygen\Custom.mxtpro
[*] Please move or copy the newly-generated file to MobaXterm's installation path.
```

Then copy `Custom.mxtpro` to `C:\Program Files (x86)\Mobatek\MobaXterm`.

## Screenshot

![](pic0.png)

## Postscript

1. This application does not have complex activation algorithm and it is truly fantastic. __So please pay for it if possible.__

2. The file generated, `Custom.mxtpro`, is actually a zip file and contains a text file, `Pro.key`, where there is a key string. 

3. `MobaXterm.exe` has another mode. You can see it by adding a parameter `"-customizer"`.

   ```
   $ .\MobaXterm.exe -customizer
   ```

   I don't know how to make custom settings take effect in `Customizer` mode directly. 
   
   The only way I found is that you should export custom settings to a file named `MobaXterm customization.custom` which is also a zip file. Then merge two zip file: `Custom.mxtpro` and `MobaXterm customization.custom` to `Custom.mxtpro`. Finally copy newly-generated `Custom.mxtpro` to MobaXterm's installation path.

<<<<<<< HEAD
地址  https://www.52pojie.cn/thread-812140-1-1.html

本帖最后由 doublesine 于 2018-10-25 14:05 编辑


尽管在52pojie上已经有人针对MobaXterm写出了暴力破解方案，但是因为牵扯到修改代码段所以我并不喜欢。
这是我根据逆向出来的注册算法写出来的注册机，无需对程序有任何修改，所以安全性有足够保障。

注册机会在我的github上维护，有问题可以发issue或者在本帖下发帖也行。
https://github.com/DoubleLabyrinth/MobaXterm-keygen

----------------分割线---------------------

注册机的话是一个python3脚本，用法很简单，在命令行下：

要安装 python3   
下载
安装 https://www.python.org/ftp/python/3.7.3/python-3.7.3.exe

MobaXterm-Keygen.py <UserName> <Version>

<UserName>的话是授权用户名，这个随你填
<Version>是MobaXterm的版本号，例如"10.9"或者"11.0" "11.1"

例如：

./MobaXterm-Keygen.py unRMBPlayer 11.1

./MobaXterm-Keygen.py "DoubleSine" 10.9

然后会在当前目录下生成一个Custom.mxtpro文件，把这个文件放到MobaXterm的安装目录下即可。

  

成功的话应该是这个样子：
[*] Success!
[*] File generated: G:\MobaXterm\Custom.mxtpro
[*] Please move or copy the newly-generated file to MobaXterm's installation path.

最后我说几句题外话：

这个软件还是很良心的，注册算法不难，而且程序被修改了还会给你安全警告，所以能付费的话就付吧。

MobaXterm的话还有一个Customizer模式。可以用

MobaXterm.exe -customizer

打开，但是里面的配置没法直接生效（如果有人知道为什么可以说说）。
我所能想到的唯一办法是在Customizer模式将设置导出为"MobaXterm customization.custom"文件（本质是zip文件）
然后和"Custom.mxtpro"文件（本质也是zip文件）合并，并放到MobaXterm的安装目录下。
=======
地址  https://www.52pojie.cn/thread-812140-1-1.html

本帖最后由 doublesine 于 2018-10-25 14:05 编辑


尽管在52pojie上已经有人针对MobaXterm写出了暴力破解方案，但是因为牵扯到修改代码段所以我并不喜欢。
这是我根据逆向出来的注册算法写出来的注册机，无需对程序有任何修改，所以安全性有足够保障。

注册机会在我的github上维护，有问题可以发issue或者在本帖下发帖也行。
https://github.com/DoubleLabyrinth/MobaXterm-keygen

----------------分割线---------------------

注册机的话是一个python3脚本，用法很简单，在命令行下：

要安装 python3   
下载
安装 https://www.python.org/ftp/python/3.7.3/python-3.7.3.exe

MobaXterm-Keygen.py <UserName> <Version>

<UserName>的话是授权用户名，这个随你填
<Version>是MobaXterm的版本号，例如"10.9"或者"11.0" "11.1"

例如：

./MobaXterm-Keygen.py unRMBPlayer 11.1

./MobaXterm-Keygen.py "DoubleSine" 10.9

然后会在当前目录下生成一个Custom.mxtpro文件，把这个文件放到MobaXterm的安装目录下即可。

  

成功的话应该是这个样子：
[*] Success!
[*] File generated: G:\MobaXterm\Custom.mxtpro
[*] Please move or copy the newly-generated file to MobaXterm's installation path.

最后我说几句题外话：

这个软件还是很良心的，注册算法不难，而且程序被修改了还会给你安全警告，所以能付费的话就付吧。

MobaXterm的话还有一个Customizer模式。可以用

MobaXterm.exe -customizer

打开，但是里面的配置没法直接生效（如果有人知道为什么可以说说）。
我所能想到的唯一办法是在Customizer模式将设置导出为"MobaXterm customization.custom"文件（本质是zip文件）
然后和"Custom.mxtpro"文件（本质也是zip文件）合并，并放到MobaXterm的安装目录下。
>>>>>>> d498131b206a01b315f386e9be1511b6058ac6c5
