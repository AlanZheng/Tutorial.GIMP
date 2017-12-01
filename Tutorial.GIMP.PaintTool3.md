GIMP教程之"涂画工具"（3）| GIMP tutorial -- Paint Tools (3)

![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

Summary:

In this tutorial, I will introduce the other 5 advanced paint tools: **Heal**, **Perspective Clone**, **Blur/Sharpen**, **Smudge** and **Dodge/Burn**, as below picture:

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512098183/bxjeg8nu88pn8emthjbp.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512098348/c3sbkcwybxmsjshly1jt.png)

（1）**复原**工具：

比如有下面一幅图片，想要把图片中红色圈选的部分移除掉。可以用**选区覆盖+模糊**，也可以用**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)+模糊**。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512098692/m1yibfqggzvshwsuidon.png)

用**选区覆盖+模糊**，在被移除的对象区域附件选择一个适当的选区，并且将选区旋转到与被移除对象相近的角度，将选区覆盖到被移除对象上面，然后用**模糊**工具将选区边缘做模糊处理，使其与背景柔和的融和。如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512099303/gkqkb4vjvhanukeyrwp5.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512099755/wt8tsyyvmddlwvjtypt3.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512099953/hylrgm5mxus4ewrah6tb.png)

用**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)+模糊**，在被移除对象附近选择克隆源，然后对被移除对象进行涂刷，最后用**模糊**工具做柔和处理。如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512100538/zwdtiai9kdqdohdr3adq.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512100620/nbv9qrnqipyjegd9puq6.png)

尽管这个2种方法都可以，但是很麻烦，并且处理微小细节的时候过渡不自然。下面介绍如何用**复原**工具来简化并且效果更好的处理。

**复原**工具跟**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)**工具用法非常相似，也是用Ctrl+鼠标左键来选择源，然后在被移除对象上进行涂抹。但是涂抹的过程会发现涂抹出来的结果跟目标区域颜色融合的更柔和，不像**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)**工具完全克隆源区域。这也就是**复原**工具跟**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)**工具最大的区别，它更像是一个“聪明”的**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)**工具（**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)**+与背景融合）。对其详细算法的介绍可以参考[GEORGIEV01](https://docs.gimp.org/2.8/zh_CN/bibliography.html#bibliography-online-georgiev)

处理最大的红色块区域结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512102366/bevqk4hlbybxnoktiaqj.png)

最终处理全部红色区域的结果如下：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512103945/ejouqmph5e9ldhni93v8.png)

关于**复原**工具的工具选项请参考**[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)**工具，它们的工具选项设置一样。

（2）**透视克隆**

比如有下面一幅图片，我们想要把画框里面最右面的一幅画克隆到最左边的空白处。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512104750/fkpydb3cisrh5vzbhgy5.png)

看过前面的[选择工具(1)](https://steemit.com/utopian-io/@alanzheng/gimp-1)和[选择工具2](https://steemit.com/utopian-io/@alanzheng/gimp-2)后，我们有各种选择方法可以将最右面的一幅画选中，然后拷贝粘贴到最左边的空白处。或者用前面的[克隆工具](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)克隆到最左边的空白处。

拷贝粘贴：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512106226/waghanot1d27dsws0xrw.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512106337/a2kh6clz4ghlnuqsbdqd.png)

克隆：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512107009/bwqoitrx0ef1ipx6lmbl.png)

但是，看起来有点奇怪，这个画框不是从正面拍摄的，是从侧面拍摄的。因此左边大右边小，有透视效果。如果只是简单的拷贝粘贴或者克隆的话，新画跟最右面的画一样大，这显然不合常理。当然我们可以用后面即将讲到的**透视变形**处理，但是很麻烦，因为需要知道透视角度。

下面介绍如何使用**透视克隆**来实现，选择**透视克隆**工具后先在工具选项上设置**修改透视**，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512107301/vmhxejx9fzinu9nvjncl.png)

点击图片后会出现一个可调整的选择框，注意图像周围四角。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512107479/k6zbe3cnigjxvwoktqqe.png)

调整选择框的四个角到如下图所示：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512107666/jmfzxqzaut9clmkw65o5.png)

将工具选项设置为**透视克隆**，并且选择克隆源点：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512107761/r7lmk1rgunfvocrh0crg.png)

然后将其克隆到最左边的空白处，可以看到**透视克隆**，跟拷贝粘贴，以及[克隆](https://utopian.io/utopian-io/@alanzheng/gimp-2-or-gimp-tutorial-paint-tools-2)有明显的差异。**透视克隆**是按照设定的透视角克隆的。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512108208/led5in2svd4fatzc65la.png)

（3）**模糊/锐化**工具，在工具选项上选择**模糊**

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512109680/jtyqwx7kjvukueqh61qm.png)

然后用光标在画框和墙结合的部分进行涂抹，可以看到光标处画框和墙有相融合的过渡色。**锐化**是使颜色之间的层次更加分明，差异更加突出。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512109902/scsl30zw5btsehmwhpf7.png)

（4）**涂抹**工具，用来将一种颜色涂抹融入到另一种颜色中，如下图，将黑色的画框涂抹融入到墙体中。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512110840/iax2hkzz31bkesrvgcgd.png)

（5）**减淡/加深**工具，用来调整被涂刷部分的亮度或者暗度。关于工具选项**画笔**部分的设置请参考[GIMP教程之"涂画工具"（1）](https://steemit.com/utopian-io/@alanzheng/gimp-1-or-gimp-tutorial-paint-tools-1)

减淡：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512111582/eeppn66njlgebhg9thbs.png)

加深：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1512111636/apmb2gqt9auxxuzdxmbq.png)