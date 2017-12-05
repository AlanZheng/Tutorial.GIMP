GIMP教程之"涂画工具"（2）| GIMP tutorial -- Paint Tools (2)

![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

Summary:

In this section I will introduce the first advanced Paint Tools: **Clone** tool.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511921866/mhrwbqnjswboz0lwn9km.png)

---
</br>

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511952210/vn31u8wlhefyqjsfdzyc.png)

（1）**克隆**工具

克隆工具的使用是先选择克隆，然后在目标区域涂刷。这样源区域的图像就会被完全克隆到目标区域了。

选择**克隆**工具，按键盘上的Ctrl键并且按下鼠标左键选择克隆源，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511948480/rynyvsfbinvybe54taz1.png)

然后在下面的目标区域涂刷，那么克隆源部分的图像就完全被克隆到目标区域了，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511948850/ryleoftlzzvn7lcgz4sf.png)

关于画笔部分的工具选项设置和**位样合并**请参考：[GIMP教程之"涂画工具"（1）](https://utopian.io/utopian-io/@alanzheng/gimp-1-or-gimp-tutorial-paint-tools-1)

**克隆**工具需要注意的部分是工具部分的**对齐**设置，默认设置是**无**，还有3个选项，分别是：**已对齐**，**已记录**，**固定**。

**已对齐**是什么意思呢？要解释这个选项，我们再看一个用默认设置**无**克隆的结果：

选择克隆源，**注意比刷尺寸**

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511951500/qqpa9veet9dky35ebnva.png)

如果克隆过程中需要改变笔刷尺寸，然后再接着克隆，我们会发现接着克隆的图像跟改变笔刷前克隆的图像没法连续，完全变成一个新的克隆了。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511951305/sgii1wpiowhp8lmembb6.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511951394/frllx6fe9ktmood5aift.png)

这种情况在实际中经常会遇到，比如我们要用克隆工具对一个区域进行克隆的时候，会先用大笔刷克隆大面积区域，提高速度。克隆细节部分的时候需要调整笔刷的大小。通常会改小，但是如果没法跟之前的克隆连续，这会是一个非常糟糕的问题。要解决这个问题，需要设置克隆工具选项为**已对齐**。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511950824/ppisu0pm2sxrcen3v0zd.png)

这时还是先用大笔刷克隆，然后改小笔刷克隆，可以看到大小笔刷克隆是完全连续的。如图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511951119/quxypfhvull2dysg8zgm.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511950956/vffeejuklwbwtdeb6a06.png)

**已记录**是用在图层之间克隆。选择克隆源，并且工具选项设置为**已记录**，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511952502/uxvnxd1mrkgj3szylfcx.png)

然后新建一个图层，并且设置为工作图层，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511952609/aakyhpufswtnlq7nih92.png)

然后在新图层中克隆，可以看到克隆源被克隆到新图层了，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511952728/ft41cx05b2mv8rqfcsiu.png)

这个操作看起来跟用选择工具，然后粘贴为新图层比较相似，其实不然。粘贴为新图层总是会把粘贴部分放在新图层的起始位置。而用**已记录**克隆，被克隆图像在新图层放在跟源图像同样的位置。比如我把图像放在图层中间位置，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511953129/hj5wyraxygyfhlhcxeej.png)

用粘贴为新图层，结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511953196/yxugydfcsmnntvempwlx.png)

用**已记录**克隆，结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511953294/ukwvvkuopc5z1mw6jj9z.png)

最后一个是**固定**选项，选择如下克隆源：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511953428/alsrtnlthbqfyxm1qruz.png)

克隆结果如下，可以看到克隆工具只克隆选择源**固定点**处的图像。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511953563/w6ujoghto2mhbft2pvki.png)

上面所有的克隆都是对源图像的克隆。
**克隆**工具可以对给定图案克隆，这时克隆工具就变成一个带图案的笔刷，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511958940/hvwzrybsr2erxle3ve2e.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511959017/weptddz3sekkn6mup7nt.png)

图案克隆可以对剪贴板上的图像进行克隆，比如在剪贴板上有如下选中的图像：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512004991/gl9ajufntnwpsf3gtjmc.png)

将该选择部分复制到剪贴板，然后选择**克隆**工具，在工具选项部分选择**图案**，图案源部分选择剪贴板。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512005136/yxdzqmgcmcb02udvlesh.png)

然后进行克隆，可以看到剪贴板上的图像被克隆如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512005423/nqrbwzsjon8ys0v5wcld.png)

