GIMP教程之"变换工具" | GIMP tutorial -- Transform Tools

![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

Summary:

In this tutorial, I will introduce the 9 transform tools: **Align**, **Move**, **Crop**, **Rotate**, **Scale**, **Shear**, **Perspective**, **Flip** and **Cage Transform** as below picture:

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512271199/ejxh0zow5zuzh6usejhp.png)

---
</br>

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512271690/cstcqivtwfiddsduff1e.png)

（1）**对齐**工具，在一幅图片中如果有许多元素的时候，对各元素进行布局需要用到对齐工具来提高效率，GIMP中的对齐工具如下图。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512272363/lglknkr4tvqbyslk4xlh.png)

比如我们需要将上面图片中的红色和黄色的圆左边对齐。在**对齐**工具选项中选择**第一项**，先用鼠标选择红色圆，然后按下Shift键并且选择黄色的圆。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512272669/eygzvhgly64468kfqepp.png)

接着在**对齐**工具选项中选择**对齐目标的左边缘**，结果如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512272708/k22pgkkwttxh1wesjw1x.png)

如果我们需要将红色和黄色的圆放在同样的高度，并且2圆相距1000像素呢？
还是在**对齐**工具选项中选择**第一项**，先用鼠标选择红色圆，然后按下Shift键并且选择黄色的圆。并且在**位移**处设置1000，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512273522/b6nhggei8blgly5bzfyv.png)

接下来选择**对齐目标的上边缘**，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512273752/jm6xnknfmet1xqxzupkq.png)

然后选择**分布目标的左边缘**，最终结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512276581/al1bsdoukr9z89vlly8o.png)

**对齐**工具选项中的**图像**选项表示被选对象相对于整个画布区域对齐。比如要把红色圆放在画布中居中，接下来选择**对齐目标中央**和**对齐目标中部**，对齐结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512277211/p4wzmbwh87kr9doibrsr.png)

**对齐**工具选项中的**选区**选项表示被选对象相对于一个选择区域。比如要把红色圆放在一个选区的中央，接下来选择**对齐目标中央**和**对齐目标中部**，对齐结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512277466/iita2fykxnfw5kill0u1.png)

**对齐**工具选项中的**活动图层**选项表示被选对象相对于当前活动图层。比如要把红色圆与GIMP文字图层左边缘对齐，接下来选择**对齐目标的上边缘**，对齐结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512277630/oeijmdpsmndvxuw72eqf.png)

（2）**移动**工具：

**移动**工具使用比较简单，可以在工具选项上设置移动**图层**，**选区**或者**路径**。在选择目标上可以选择图层或者参考线。当鼠标指针放在移动目标上并带有十字光标的时候就可以移动物体了。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512278061/b2fcckaxyuozppp40eu2.png)

（3）**裁剪**工具：

**裁剪**工具用于更改画布尺寸，使用方法跟矩形选择工具类似，请参考[GIMP教程之"选择工具"（1）](https://steemit.com/utopian-io/@alanzheng/gimp-1)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512279209/mbdwx9lcfvieddrw1uhc.png)

设定好选择区域后，在选区内点击鼠标左键确认选区。裁剪结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512279326/euo7rnltvbeatikm8thq.png)

需要注意的是**裁剪**工具选项中的**允许增长**，设定该选项后选区可以大于当前画布尺寸，如下图，不然的话选区只能小于后者等于画布区域。也就是说选择**允许增长**后可以扩大画布尺寸，不选的话只能缩小画布。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512279460/qdxnfk2nwv0ojh7bfqmh.png)

（4）**旋转**工具，可以在工具选项上选择旋转**图层**，**选区**或者**路径**，选取旋转目标后在目标上会出现网格以及旋转中心点，在旋转目标上拖动鼠标左键，旋转目标会绕着旋转中心点旋转。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512280028/w8wktd9nh0u3nixour4h.png)

在**旋转**对话框上选择**旋转**后结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512280372/emyhskqfjdy1oqgggchv.png)


（5）**缩放**工具：可以在工具选项上选择旋转**图层**，**选区**或者**路径**，选取缩放目标后在目标上会出现网格以及移动中心点，在缩放目标上拖动网格四周的缩放手柄。就可以对目标进行缩放。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512280625/os32m0kyhftxjb49anzu.png)

确定后缩放结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512280890/lelnzonoje3mxnwkqqxt.png)

（6）**切变**工具，用于对目标变形，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512280972/bquu6t2iaqdwymxvdted.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512281048/jjyl9dsapkysrbfmbiuw.png)

（7）**透视**工具，用于对目标透视变形，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512281139/wobktzgb4yf6smyv11q7.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512281160/nwnoxdqbqpiqz4qzcjkx.png)

（8）**反转**工具，用于对目标做水平或者垂直反转，鼠标左键选择目标就可以做反转。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512281291/dg4f8qvkz6tokaiie9bn.png)

（9）**Cage变换**工具，用于对目标做自由变换。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512281460/jgf96kjfe6wmrwexaaqu.png)

选区选择类似与**自由选择工具**，请参考[GIMP教程之"选择工具"（1）](https://steemit.com/utopian-io/@alanzheng/gimp-1)，选区封闭后可以移动选择手柄对选区做自由变换，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512281556/imbkgw3a3css7zmn87nl.png)

