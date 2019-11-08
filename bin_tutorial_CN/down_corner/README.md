### 2: 解决底面白色角块
您的目标：
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:5678,edge:5678,center:23456}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

在完成底层十字后,接下来需要还原底层角块,现根据颜色找到目标角块,再把目标角块放到上前右(UFR)的位置,我们的目标是把上前右的角块转动到下面也就是DFR的位置,这样就共有3种case,对应有3个公式,用这3个公式您会发现原有的底层十字依旧完好不会被打乱.<BR>


- Case1 白色角块在F(前）<span style="color: red;">**URU'R'**</span>
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:5678,center:123456,monitorCorner:8,cornerDirAndPath:<884,formula:URU'R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 白色角块在R(右) <span style="color: red;">**RUR'**</span>
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:5678,center:123456,monitorCorner:8,cornerDirAndPath:>884,formula:RUR'}
" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 白色角块在U(顶) <span style="color: red;">**RU2R'U'RUR'**</span>
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:5678,center:123456,monitorCorner:8,cornerDirAndPath:84,formula:RU2R'U'RUR'}
" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

您可能会遇到目标角块已经在底层的情况,没有办法转动到UFR的位置,你可以用上面介绍的任何一个公式把底层的角块给挤出到顶层,再转成上面的3种case继续处理.
