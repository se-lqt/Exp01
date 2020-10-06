# Exp_01/实验1_Android开发基础

### 一、实验内容

搭建Android开发环境、创建第一个Android工程并同步GitHub

### 二、实验步骤

#### （一）安装Android Studio（AS）

1.Android Studio3.5.2下载链接http://www.android-studio.org/

直接点击下载即可

![RUNOOB 图标](https://i.loli.net/2020/10/05/xPcLVe2nDCXbaZT.png)

2.安装过程

![RUNOOB 图标]( https://i.loli.net/2020/10/05/Q7UeMvLsJmIdWPu.png)

![3.png](https://i.loli.net/2020/10/05/CZiuc7MXRylGsqm.png)

选择安装的位置，一路next即可

![5.png](https://i.loli.net/2020/10/05/Wr6DZfBgkRbYo5O.png)

安装好后进行配置

![7.png](https://i.loli.net/2020/10/05/tVjzMawBQG6TxYS.png)

选择风格

![8.png](https://i.loli.net/2020/10/05/k4Mf6wSU9t1V2a3.png)

全部勾选，并选择SDK安装位置

![9.png](https://i.loli.net/2020/10/05/gv9KwGs2ZQNbzlF.png)

点击next开始安装SDK，等待安装完成即可。

![10.png](https://i.loli.net/2020/10/05/UF2EXp7huI5BcOW.png)

接下来打开Android Studio,新建一个项目

![11.png](https://i.loli.net/2020/10/05/pTvWSFb2Gh8InDK.png)

命名相关信息，语言要选择 Java,点击finish

![12.png](https://i.loli.net/2020/10/05/vkjXcszTarNtFZO.png)



#### （二）添加模拟器

接下来添加模拟器，可用Android Studio自带的，也可用Genymotion，此处用软件自带的

![模拟器1.png](https://i.loli.net/2020/10/05/icRxtfMZLTqCKu4.png)

添加

![模拟器2.png](https://i.loli.net/2020/10/05/enCg3mpSf2saw5H.png)

选择尺寸

![m1.png](https://i.loli.net/2020/10/05/6yEQn9vCGNYiudl.png)

这边可直接next（有时需要下载，下载即可）

![m2.png](https://i.loli.net/2020/10/05/UwIOuLj7vn15zFt.png)

点击finish即可（也可调整其他信息）

![m3.png](https://i.loli.net/2020/10/05/b8Bgc7JOpk2iCVl.png)



#### （三）运行第一个项目

创建一个Android项目，AS默认内容为"Hello world",点击运行run即可

![m3.png](https://i.loli.net/2020/10/05/iwx1rh5Z9fALvHG.png)

运行效果如下

![14.png](https://i.loli.net/2020/10/05/nk1EUMWruxAtJ4w.png)



#### （四）将第一个项目同步到github上

下载git，下载链接 https://gitforwindows.org/，安装过程一路next即可。

安装好后，选择git bash打开

![git.png](https://i.loli.net/2020/10/05/pVFQA2t8vkKnj4S.png)

安装下面命令，配置好用户名和邮箱

```
git config --global user.name "用户名"

git config --global user.email "邮箱"

git config --list 查看信息 检查是否创建成功
```

![21.png](https://i.loli.net/2020/10/05/hrzGD28f3tqkAug.png)

没有账号要先注册一个

![26.png](https://i.loli.net/2020/10/06/VEXJQzfNsKOtI1L.png)



接着创建一个仓库

![15.png](https://i.loli.net/2020/10/06/m41rHToEVAgFI9Q.png)

![16.png](https://i.loli.net/2020/10/06/IP1cxqasBnKfo5w.png)

复制下网址等下备用（ssh方式上传也可以，操作略有不同）

![18.png](https://i.loli.net/2020/10/06/jeAIXP85UJbonOf.png)



找到项目文件所在目录，右键打开git bash，输入git clone 网址    克隆

![__SMX3_7_Q6VNJT_RH_0_FU.png](https://i.loli.net/2020/10/06/QqFLTIlXHD2tp5a.png)

文件夹就会出现git hub创建的仓库名，讲要上传的文件移到该文件夹

```
cd  切换文件目录
git add . 添加要上传的文件，此命令是上传全部
git commit -m "提交说明"   提交
```



![20.png](https://i.loli.net/2020/10/05/knD6GCso8v1Z7Af.png)

接下来 git push 传到github仓库上

![23.png](https://i.loli.net/2020/10/06/yovGD8rXx31Ieja.png)

需要输入github的账号密码

![22.png](https://i.loli.net/2020/10/06/3E7DKWYqxdSRwm6.png)

上传成功

![24.png](https://i.loli.net/2020/10/06/fxNomQLWUg4FX3T.png)



