![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

前段时间在做视频处理，需要在视频中加入图片，要求每张图片大小一致。本来打算用程序自动处理，打开每张图片大致浏览了一下，放弃。因为每张图片中所需要的部位不一样。瞬间感觉在电脑上工作其实根本就是一个体力活。但是本着偷懒的原则，还是尽量少费点体力。

隆重推荐[GIMP](https://www.gimp.org)--开源界的PhotoShop：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511494245/gvrsurkb1g8vj9usedkh.png)

好的PS图片是从好的“选择”开始的，GIMP里面的选择工具很丰富，基于这次的任务需要先介绍固定大小选择。

启动GIMP后会看到工具栏上的这7个图标，分别是：

（1）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611095/yhtgks6ibt5sikcbji4f.png)

（2）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611168/yigpxspfrxfcqgb6vcxg.png)

（3）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611221/gtg9ujgmsdtw2nrn3qff.png)

（4）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611282/xwu76odhxpvjsxrj45oc.png)

（5）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611442/abko0tgtuyfbseblhwiv.png)

（6）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611489/vkauoqtr5krm1pjrmtit.png)

（7）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511611539/albyhplfavlil4dqqlaj.png)

把所有的图片全部作为图层打开

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511583815/uxsb1mtrnpfdu4gbcnrt.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511584090/ix5pf7gywdjga8riyzk8.png)

然后在“矩形选择工具”选项中使用“固定大小选择”。工具及设置选择如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511512197/znieeqazfnbfvtr9ndkp.png)

把选择好的图片粘贴为新图片，然后保存即可。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511584538/egwnfypvhjyvglf5vacr.png)

到这里本文开始部分的任务完成了。

***


接下来介绍前3个基本“选择工具”，分别是矩形，椭圆，和自由选择工具，这3个选择工具有类似的操作，都是通过拖动鼠标来形成一个封闭的区域形成选区。

（1）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511492365/xdo4myzu94rh86vxkvgm.png)

（2）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511492395/b1dcfj11s1gn0ygdngpj.png)

（3）![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511492426/mefasqmnofkggryo6eqd.png)

默认设置选择如下图所示：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511585306/kvzipeysctpwppz0gw15.png)

下面左边黑色选区是**没有设定**“边缘平滑”，有边选区是**设定了**“边缘平滑”的对比，可以看到左边选区比右边选区边缘部分锯齿现象明显。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511662584/gcvbdxoaj0qs5ygv3uw3.png)

需要注意的是”边缘羽化“，默认GIMP“选择工具”选项中不设定“边缘羽化”，效果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511585671/f1iuuvnjtdswzvff5bra.png)

设定“边缘羽化”为20，效果如下。对比可以看到，设定“边缘羽化”后在选区的边缘处会有一个明显的颜色过渡。看起来更柔和一些。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511587545/b92tjreiszrpghns1rqn.png)

设定固定宽高比时可以做正方形和圆形选择，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511612158/gwg1o3biubbiacoxxujb.png)

需要对选区做准确定位的时候可以设置显示中心线，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511612399/gh6y6zqiqvepujk4zmrt.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511612454/fjuxafc2pzyetffzfsma.png)

对2个或者多个选区做合并，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511612606/gtslh3nl9emttzgze5hc.png)

用前一个选区减去后面其他的选区，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511612735/usone1kzdi7zwy3jicfg.png)

对多个选区求交，如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511612824/avdvzcyunupsmu4f0sfy.png)

<br /><hr/><em>Posted on <a href="https://utopian.io/utopian-io/@alanzheng/gimp-1">Utopian.io -  Rewarding Open Source Contributors</a></em><hr/>