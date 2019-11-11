### 5: 解决顶层所有黄色
通过上一步您已经得到了一个顶层十字,这一步您的目标是复原整个顶面黄色,您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U}}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

这一步也只需要一个公式 <span style="color: red;">**RUR'URU2R'**</span>,具体的情况请参考图示.


- Case1 顶层已经有一个特殊的小鱼图案,把鱼头放在FR(前左)的位置,注意角块UFR(上前右)的黄色朝向的是前面,这条鱼是一条真正的小鱼,运用下面的公式就可以得到完整的顶层.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:<2<3<4,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case2 顶层有一个特殊的假小鱼,把鱼头放在FR(前左)的位置,注意角块UFR(上前右)的黄色朝向是右面,这条鱼是一条假的小鱼,运用下面的公式就可以得到真的小鱼,然后再用真小鱼的方法处理.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:>2<3<3>4,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case3 顶层有一个十字,UFL(上前左)的黄色朝向左,UFR(上前右)的黄色朝向右,如下图,用这个公式后就可以得到一条真正的顶层小鱼,然后在按照Case1的方法处理.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:<2>3>4,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case4 顶层有2个角块的颜色不对,UFL(上前左的黄色朝向左),UBL(上后左)的颜色朝向左,这种情况运用这个公式后就可以转变为Case3,然后再用Case3的方法处理.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:>2,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case5 顶层有2个角块的颜色不对,UFL(上前左的黄色朝向前),UBL(上后左)的颜色朝向后,这种情况跟Case4很相近,运用这个公式后就可以转变为Case2(假的小鱼),然后再用Case2的方法处理.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:<2,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case6 顶层有2个角块的颜色不对,UFL(上前左),UBR(上后右)的颜色不对,运用这个公式后就可以转变为Case3(顶层十字),然后再用Case3的方法处理.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:>3,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

到此9个公式中您已经学会7个,再学习2个公式就可以完整的还原了. :)
