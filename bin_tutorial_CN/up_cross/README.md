### 4: 解决顶层黄色十字
您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U}}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

所谓顶层十字,就是把所有的黄色棱块,都翻到顶层,不用考虑顶层角块,这一步只需要一个公式<span style="color: red;">**FRUR'U'F'**</span>,具体解法请参考图示


- Case1 顶层已经有一个一字
运用下面的公式就可以得到顶层十字
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>3,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 顶层左后各有一个黄色
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>4,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 顶层只有中心块是黄色
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>2>3>4,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

您可能会遇到目标角块已经在底层的情况,没有办法转动到UFR的位置,你可以用上面介绍的任何一个公式把底层的角块先给挤出到顶层,再转成上面的3种case继续处理.<BR>

到此9个公式中您已经学会3个,再学习6个公式就可以完整的还原了. :)
