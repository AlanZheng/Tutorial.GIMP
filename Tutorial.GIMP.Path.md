GIMP教程之"路径工具" | GIMP tutorial -- Path Tool

![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

Summary:

In this tutorial, I will introduce the **Path** tool, and how to use **Path** and **Text** tool creating the text along path.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512732577/zjs7upqi3y729oaylfrm.png)

---
</br>

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512732446/a4jkdngspswrldfqot0a.png)

**路径**工具是用来创建曲线（Bézier-curves）的工具，路径有**控制点**，**路径曲线**（Bézier-curves），**控制手柄**构成。控制点定义了曲线的节点（小圆圈），各控制点连接起来构成路径曲线，控制手柄（小方块）可以调节曲线的曲率，方向。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512733170/x4e5zsnjjzxplxgbmasf.png)

**控制手柄**的长度控制曲线的曲率，**控制手柄**的方向控制曲线的方向。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512734425/gqol6dihdqsog1vag5o2.png)

**路径**可以是封闭的也可以是开放的，上图是封闭的**路径**，在路径工具选项中设置为**编辑**模式，然后按Shift键选择路径中任意2个节点的连线，可以将这条线删除。此时曲线变成了一个开放的路径，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512741273/ulrzyl2a3qoqelwx8nmd.png)

要将路径曲线再次封闭起来，在路径工具选项中设置为**编辑**模式，选择首节点后将鼠标移动到尾节点，注意鼠标光标形状。然后选择尾节点，曲线即可封闭。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512741666/ca2nvo4w4mlhgf73mp8w.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512741742/uob1m4ugso4hyw3jwomh.png)

在工具选项中选择移动，然后用鼠标选择曲线的任意位置可以移动路径曲线，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512741801/bth4er0hwwfkxjidiryi.png)

对于任意封闭的路径，在工具选项上选择**从路径创建选区**，即可创建选区。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512741888/wkggha73uuallkwvtmmi.png)

对于任意选区，可以通过**选区到路径**，将其转化为路径曲线。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512742909/fhq12ysjupyl70hgfiad.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512742980/eanbnztwlo9vaqmqxlev.png)


对于任意路径，都可以在工具选项上选择**勾画路径**将其用画笔勾画成图案。如下图：

勾画开放路径：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512742045/qktwqwldl0ehse5ykbnv.png)

勾画封闭路径：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512742087/mp0wevevjalnmfmcvucu.png)

如果在工具选项上设置**多边形**，然后创建的路径是由直线段所连接而成，不会有曲线段。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512742369/p6eru9opiivsdvm6zwpa.png)

有多个路径图层的时候，红色的是当前活动路径，蓝色的是非活动路径。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512742486/cnq7sdqzgzfyvlers09p.png)

设置工具选项**设计**模式，然后按Shift键并且拖动**控制手柄**可以将其调整为等长并且在一直线上。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512743550/xovbbcxnduteqhovalpk.png)

设置工具选择**编辑**模式，然后按Shift键并且选择**控制手柄**，可以将其删除（控制手柄回到控制点位置）。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512743790/tth8z6ythlfa1lrgq3nm.png)

多个路径图层可以通过**合并可见路径**将其合并到同一个路径图层。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512744010/hutclyh6av7fy5esqjpc.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512744054/ormgueshwpvc7gvmghsi.png)

---
</br>

下面使用**路径工具**，**选区工具**以及**文字工具**创建一个文字圆形环绕的例子：

（1）使用圆形选择工具，创建一个圆形选区。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512785729/gqlo1qagd6rqvgnzvo4o.png)

（2）将选区转为路径。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512785764/m6p42svl8hauiwdaaohp.png)

（3）在任意位置创建文字：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512786359/clrtpg4njzi3p8rke470.png)

（4）在文字图层的鼠标右键菜单中选择**文字对齐路径**

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512786457/rx80f754x7mwplb9plgc.png)

（5）文字对齐路径后将文字图层删除，得到如下结果

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512786564/cycfux9srbbut2klr9bb.png)

可以看到现在的文字已经转换为路径了，并且沿着圆弧的方向。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512786769/kcwhe1qyoa4ybrsss9eg.png)

（6）使用**旋转**工具将其旋转到圆弧的上方（注意要将旋转点移动到圆心），如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512787060/m9d2paptl8ywlzqagamt.png)

确定后得到最终文字沿圆形路径环绕的效果：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512787160/uo8k58c8lecrc0xxtdhf.png)

例子中使用的**选区工具**，**文字工具**以及**旋转工具**请参考下面：

[GIMP教程之"选择工具"（1）| GIMP tutorial -- Selection Tools (1)](https://steemit.com/utopian-io/@alanzheng/gimp-1)
[GIMP教程之"文字工具" | GIMP tutorial -- Text Tool](https://steemit.com/utopian-io/@alanzheng/gimp-or-gimp-tutorial-text-tool)
[GIMP教程之"变换工具" | GIMP tutorial -- Transform Tools](https://steemit.com/utopian-io/@alanzheng/gimp-or-gimp-tutorial-transform-tools)