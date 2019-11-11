### 7: 顶层棱块归位
顶层的4个角块归位,您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:12345678,edge:1234567890AB,center:123456}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

这是最后一步了,只有一个公式<span style="color: red;">**RU'RURURU'R'U'R'R'**</span>,把不需要交换的棱放在后面,使用公式可以把前右左三个面的顶层棱块做逆时针调换,如果找不到这样的面,使用公式一次就可以得到这样的面,使用1到2次公式魔方就还原了!!


- Case1 找到了不需要交换的棱块,把他放在后面
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeDirAndPath:24,formula:RU'RURURU'R'U'R'R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 找不到不需要交换的棱块,直接先做一次这个公式就能得到Case1,至多在做2次这个公式就可以完全的还原魔方了.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeDirAndPath:2343,formula:RU'RURURU'R'U'R'R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>


到此9个公式中您已经学会9个 :)
