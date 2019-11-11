### 4: Solve the top yellow cross
Your goal:
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U}}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>


The so-called top cross is to turn all the yellow color  to the U(up) face, regardless of the top corner block. This step only requires a formula <span style="color: red;">**FRUR'U'F'**</span>,please refer to the illustration for the specific case.


- Case1 There is already  "---" on the U
Use the formula below to get the top cross
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>3,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 There is a yellow color on left(L) and back(B)
Use the following formula to get the "---", which becomes Case1, and uses the Case1 method to get the top cross.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>4,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case3 Only the center block on the up(U) is yellow
Use the following formula to convert to Case2, and use the Case2 method to get the top cross.
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},monitorEdge:1234,monitorCenter:1,edgeDirAndPath:>2>3>4,formula:FRUR'U'F'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>


So far, you have learned 6 of the 9 formulas, and you can restore the Rubik's cube by learning 3 formulas. :)
<p style="color: #5e9ca0;"><span style="background-color: #ff0000;"><span style="background-color: #00ff00;">&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>&nbsp;&nbsp;&nbsp;</span> 6/9</p>
