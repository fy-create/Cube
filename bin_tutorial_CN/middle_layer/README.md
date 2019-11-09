### 3: 解决中间层
您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:5678,edge:567890AB,center:23456}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

完成这一层需要使用2个公式,先根据颜色找到目标棱块,再把目标棱块放到上右(UR)的位置,在根据下面2中情况来让目标棱块归位.<BR>


- Case1 UR棱块移动到前右(FR)
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:567890AB,center:23456,monitorEdge:9,edgeDirAndPath:94,formula:R'U'R'U'R'URUR}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 UR棱块移动到后右(BR)
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:567890AB,center:23456,monitorEdge:B,edgeDirAndPath:B4,formula:RURURU'R'U'R'}
" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

您可能会遇到目标棱块已经在中间层的情况,没有办法转动到UR的位置,你可以用上面介绍的任何一个公式把中间层的棱块先给挤出到顶层,再转成上面的2种case继续处理.<BR>

到此9个公式中您已经学会5个,再学习4个公式就可以完整的还原了. :)
