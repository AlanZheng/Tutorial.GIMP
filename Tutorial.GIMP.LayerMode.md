GIMP教程之"图层模式" | GIMP tutorial -- Layer Mode

![Tutorial.GIMP.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1511486986/feaponrcwwtwu0vmiizt.png)

Summary:

In this tutorial, I will introduce the layer mode, and showing how to use layer mode to change image.
GIMP has 21 layer modes as below:

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513300900/zmgasywxjqbwwxzthb7z.png)

---
</br>

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513301170/jm6jmjj7h4qifwnweger.png)

下面这个是混合层，用 ***M*** 表示。
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513301788/ylvfogxegg7vicymowfw.png)

下面这个是基层（图像层），用 ***I*** 表示。
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513301834/drfztmywdmbljtqco3ni.png)

混合后的结果用 ***E*** 表示。

（1）**正常**模式：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513302757/cwcbmxipmgg9klrek8gb.png)

**正常**模式是缺省的模式，这种模式下只有上层可见。除非降低上层的不透明度，如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513310977/if2krzy3lwlpfk8zbu1p.png)

（2）**融化**模式：将混合图层的图像以散乱的点状形式叠加到基层，对图像的色彩不产生影响，与不透明度有关。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513311200/wa5eycizihjtmg2eafpg.png)

（3）**仅变亮**模式：对混合的两个图层相对应区域颜色亮度值进行比较，取亮度较高的像素点为混合之后的颜色，使得总的颜色灰度的亮度升高，造成变亮的效果。用黑色合成图像时无作用，用白色时则仍为白色。如下图：

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513311936/swqomdvo6j1fqeaozzsr.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513311744/s1pp8xhwgehxt2pcjoqf.png)

（4）**掩蔽**模式：将上下两层图层像素颜色的灰度级进行乘法计算，获得灰度级更高的颜色而成为合成后的颜色，图层合成后的效果简单地说是高灰阶的像素显现而低灰阶不显现（即浅色出现，深色不出现），产生的图像更加明亮。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513312185/n2qrzcy3a4d3gzqx5itr.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513312054/pivvhzulpnjqseyeyykg.png)

（5）**减淡**模式：用基层像素乘以256然后再除以对应混合层的补色。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513314223/m26hwvtgrdxutpfntl4w.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513314118/docuokkilso8uzf4atur.png)

（6）**相加**模式：将混合层跟基层的对应像素简单的相加，通常用来加亮图片。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513327258/zy3tepssr0cvcrys4gtw.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513327202/ygoigkizaimogfrvyur1.png)

（7）**仅变暗**模式：对混合的两个图层相对应区域中的颜色亮度值进行比较，在混合图层中，比基层暗的像素保留，亮的像素用基层中暗的像素替换。总的颜色灰度级降低，造成变暗的效果。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513327561/wad1qwiwwjm0caw7m6cz.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513327846/h0tbpct2mbxaqod286kl.png)

（8）**相乘**模式：将上下两层图层像素颜色的灰度级进行乘法计算，获得灰度级更低的颜色而成为合成后的颜色，图层合成后的效果简单地说是低灰阶的像素显现而高灰阶不显现（即深色出现，浅色不出现，黑色灰度级为0，白色灰度级为255）。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328000/mi3q66keabacaglf2753.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328030/jlehqo0kja51ptlveydt.png)

（9）**加深**模式：用基层像素的补色乘以256，然后除以混合层像素加一，对所得的结果再取补色。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328226/zg1mz4qfn98t55aynadq.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328294/jp37ahidcrjes7b1zx0d.png)

（10）**覆盖**模式：根据基色图层的色彩来决定混合色图层的像素是进行正片叠底还是进行滤色，一般来说，发生变化的都是中间色调，高色和暗色区域基本保持不变。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328508/tvr8gm33bzf9cxhy1g66.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328536/qwwvtyc53vlz05vzu71o.png)

（11）**柔光**模式：将混合色图层以柔光的方式加到基色图层，当基色图层的灰阶趋于高或低，则会调整图层合成结果的阶调趋于中间的灰阶调，而获得色彩较为柔和的合成效果。形成的结果是：图像的中亮色调区域变得更亮，暗色区域变得更暗，图像反差增大类似于柔光灯的照射图像的效果。变暗还是提亮画面颜色，取决于混合层颜色信息。产生的效果类似于为图像打上一盏散射的聚光灯。如果混合层颜色（光源）亮度高于50%灰，基色层会被照亮（变淡）。如果混合层颜色（光源）亮度低于50%灰，基色层会变暗。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328792/j1rgq0onccxaafnmynfr.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328820/nga1ilpyxxfwansfhbgk.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328696/xpx7wlckumz3rsznkdpo.png)

（12）**硬光**模式：如果两层中颜色的灰阶是偏向低灰阶，作用与正片叠底模式类似，而当偏向高灰阶时，则与滤色模式类似。中间阶调作用不明显。正片叠底或者是滤色混合基层颜色，取决于混合层颜色。产生的效果就好像为图像应用强烈的聚光灯一样。如果混合层层颜色（光源）亮度高于50%灰，图像就会被照亮，这时混合方式类似于滤色（Screen）模式。反之，如果亮度低于50%灰，图像就会变暗，该模式能为图像添加阴影。如果用纯黑或者纯白来进行混合，得到的也将是纯黑或者纯白。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328919/kwsgulo5ov3la3h1dqge.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328951/x9kdefwgj0sgy0xshzk8.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513328884/jqwkyx2rv6ofj6jel5dc.png)

（13）**差值**模式：将混合色与基色的亮度进行对比，用较亮颜色的像素值减去较暗颜色的像素值，所得差值就是最后效果的像素值。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329044/vnkdo3ymcujq8gxzzear.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329012/ttn5v7l5rxykwfzzzxt1.png)

（14）**减去**模式：作用是查看各通道的颜色信息，并从基色中减去混合色。如果出现负数就归为零。与基色相同的颜色混合得到黑色；白色与基色混合得到黑色；黑色与基色混合得到基色。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329133/xe03ev9lotnnuwy2ixfk.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329096/if3gfcyjpoczertpdf4b.png)

（15）**增益提取**模式：从基层颜色中减去混合层颜色，然后再加上128

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329211/zqs5kbsuhyrdidjvagag.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329180/ffnp1srwryqsj0bm8jmv.png)

（16）**增益合并**模式：从基层颜色加上混合层颜色，然后再减去128

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329275/mkab5zbautr7mutkawy6.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329255/xcx2ex3zgscmv3kjeub1.png)

（17）**相除**模式：模式的作用是查看每个通道的颜色信息，并用基色分割混合色。基色数值大于或等于混合色数值，混合出的颜色为白色。基色数值小于混合色，结果色比基色更暗。因此结果色对比非常强。白色与基色混合得到基色，黑色与基色混合得到白色。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329391/n6tmtjlwph4guditovzy.png)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329324/h9wdrjx8lsvb7i8njabw.png)

（18）**色调**模式：合成时，用混合图层的色相值去替换基层图像的色相值，而饱和度与亮度不变。决定生成颜色的参数包括：基层颜色的明度与饱和度，混合层颜色的色相。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329444/oc1xskcw83cy91udlea6.png)

（19）**饱和度**模式：用混合图层的饱和度去替换基层图像的饱和度，而色相值与亮度不变。决定生成颜色的参数包括：基层颜色的明度与色相，混合层颜色的饱和度。饱和度只控制颜色的鲜艳程度，因此混合色只改变图片的鲜艳度，不能影响颜色。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329489/psfq7udjglizruy1cssv.png)

（20）**颜色**模式：用混合图层的色相值与饱和度替换基层图像的色相值和饱和度，而亮度保持不变。决定生成颜色的参数包括：基层颜色的明度，混合层颜色的色相与饱和度。这种模式下混合色控制整个画面的颜色，是黑白图片上色的绝佳模式，因为这种模式下会保留基色图片也就是黑白图片的明度。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329526/orbooh5wbscgonnio56q.png)

（21）**明度**模式：用当前图层的亮度值去替换下层图像的亮度值，而色相值与饱和度不变。决定生成颜色的参数包括：基层颜色的色调与饱和度，混合层颜色的明度。跟颜色模式刚好相反，因此混合色图片只能影响图片的明暗度，不能对基色的颜色产生影响，黑、白、灰除外。

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513329565/rn62yzpvifzcqmbvspof.png)

最后用一个例子看一下图层模式的应用。

混合层：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513332665/gnjdsm6srzluaeghmu0z.png)

基层（图像层）：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513333372/u4itagzpqtrqkbcaugi0.png)

将混合层不透明度设为80%，并采用**仅变亮**模式做图层混合，结果如下：
![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1513333162/vgk82a28sbhnwwcmxiln.png)
