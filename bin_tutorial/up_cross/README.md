### 4: 解决顶层黄色十字
您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U}}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

所谓顶层十字,就是把所有的黄色棱块,都翻到顶层,不用考虑顶层角块,这一步只需要一个公式<span style="color: red;">**FRUR'U'F'**</span>,具体解法请参考图示


- Case1 顶层已经有一个一字
运用下面的公式就可以得到顶层十字
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>3,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 顶层左后各有一个黄色
运用下面的公式就可以得到顶层一字,这样就变成了Case1,在用Case1的方法得到顶层十字.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>4,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case3 顶层只有中心块是黄色
运用下面的公式就可以转变为Case2,在用Case2的方法得到顶层十字.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>2>3>4,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>


到此9个公式中您已经学会6个,再学习3个公式就可以完整的还原了. :)
