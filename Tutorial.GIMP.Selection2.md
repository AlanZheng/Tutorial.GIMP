![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

[GIMP教程之“选择工具”（1）](https://utopian.io/utopian-io/@alanzheng/gimp-1)中介绍了3个基本的选择工具：

（1）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611095/yhtgks6ibt5sikcbji4f.png)

（2）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611168/yigpxspfrxfcqgb6vcxg.png)

（3）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611221/gtg9ujgmsdtw2nrn3qff.png)

***
</br>

这部分中介绍接下来的4个高级选择工具，分别是“模糊选择工具”，“按颜色选择工具”，“剪刀选择工具”和“前景选择工具”。

（4）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611282/xwu76odhxpvjsxrj45oc.png)

“模糊选择工具”的选区是按照跟选择点颜色相似的连续颜色区域构建的。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511671351/rlbhm5lndvsprsmjmugy.png)

（5）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611442/abko0tgtuyfbseblhwiv.png)

“按颜色选择工具”的选区也是按照跟选择点颜色相似的区域构建的，跟“模糊选择工具”的区别是：“模糊选择工具”的选区是按照相似的**连续**颜色区域构建的，“按颜色选择工具”的选区是搜索**全图**的相似颜色区域，而不限制是否连续。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511671435/zsz1lg2pf0sr8b9hsgcq.png)

“模糊选择工具”和“按颜色选择工具”的工具选项一样，如下图。其中的“边缘平滑”和“边缘羽化”请参考：[GIMP教程之“选择工具”（1）](https://utopian.io/utopian-io/@alanzheng/gimp-1)，如果没有设定“选择透明区域”，那么图片中的透明区域是不能被选择的。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511675807/ipx8p10fp4m8j0h6ryel.png)

设定了“选择透明区域”，透明区域即可被选择，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511676189/mlr6nd4nbigbrjio37gt.png)

“位样合并”选项设置对颜色的选区是否在所有可见图层中选择，如下图。设置了“位样合并”后在下层的图片中点选颜色，同时上面图层中相似的颜色也会被选取。如果不设定的话，选择只在被操作的图层中进行。

“阀值”是设定与被选颜色匹配的精确度。阀值越小，颜色匹配的精确度越高，形成的选区就越小。误差较小。阀值越大，颜色匹配的精确度越低，形成的选区就越大。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511677094/acaz4bo89wy4tbx1orvb.png)

（6）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611489/vkauoqtr5krm1pjrmtit.png)

“剪刀选择工具”，这个工具跟PS中的磁性套索工具类似，会自动吸附到颜色相似的点，最终首尾闭合形成选区。非常适合用来选择复杂的选区。比如下面图片中要把狗从图片中分离处理。就可以使用”剪刀选择工具“，先通过点选而形成封闭区域。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511670692/z4f7a9ifgt5ttlrjikys.png)

然后在封闭区域内部点选，最终形成封闭的选区。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511671006/bevn0mtlkcp3ig4ksplf.png)

（7）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611539/albyhplfavlil4dqqlaj.png)

“前景选择工具”，如果要选择的选区颜色与图像其他部分反差较大适合用前景选择工具选取。如下图中狗的颜色跟背景颜色反差较大。使用”前景选择工具“，这时光标会变成“自由选择工具”，在狗的周围拖动鼠标形成一个封闭的区域，这一步是为了缩小图像的搜索范围。以提高效率和减小误差。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511673060/l7pu9xkfyacu4jekdcrh.png)

形成封闭区域后光标会变成一个笔刷的形状，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511673139/exh90pg1zl2r3oaxivbo.png)

用笔刷在要选择的前景色上进行涂抹

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511673200/x9oh5ijvdqgfk5bo85zu.png)

系统会自动在封闭区域中计算并标记出目标选区

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511674217/brplagfhbpvvqgmyuxcf.png)

如果目标选区符合预期，按Enter即可确定选区。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511674280/gk4bomxr86ugqwcn2z3l.png)

当选区大于最终需要的选区时，可以用[GIMP教程之“选择工具”（1）](https://utopian.io/utopian-io/@alanzheng/gimp-1)中介绍的选区相减并使用“自由选择工具”对选区做合适的调整，最终的选区如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511674639/dl595tcmoiuh03ueaf39.png)