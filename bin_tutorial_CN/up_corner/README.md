### 6: 解决顶层角块
顶层的4个角块归位,您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U}}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

这个步骤不用考虑顶层棱块,这一步只需要一个公式<span style="color: red;">**RB'RF2R'BRF2R2**</span>,先找到有<span style="color: red;">**两个角块相同的颜色的面**</span>,把他放在前面,用公式一次即可完成,如果找不到这样的面,做一次公式就可以得到这样的面


- Case1 顶层已经有一个两个角块相同的颜色的面,运用下面的公式就可以复原顶层角块
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:34,formula:RB'RF2R'BRF2R2}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 顶层找不到这样的面,直接做一次公式就可以得到这样的面
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:4323,formula:RB'RF2R'BRF2R2}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>


到此9个公式中您已经学会8个,再学习1个公式就可以完整的还原了. :)
