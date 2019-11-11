### 2: Solve the bottom white corner block
Your goal:
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:5678,edge:5678,center:23456}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>


After completing the bottom cross, you need to restore the bottom corner block. First find the target corner block according to the color, then put the target corner block to the up front right(UFR) position. Our goal is to turn the up front right corner block to the down front right(DFR) place, so there are 3 cases, corresponding to 3 formulas, with these 3 formulas you will find that the original bottom cross is still intact and does not be disrupted.<BR>


- Case1 White color at F (front）<span style="color: red;">**URU'R'**</span>
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:5678,center:123456,monitorCorner:8,cornerDirAndPath:<884,formula:URU'R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 White color at R (right) <span style="color: red;">**RUR'**</span>
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:5678,center:123456,monitorCorner:8,cornerDirAndPath:>884,formula:RUR'}
" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

-  Case2 White color at U(up) <span style="color: red;">**RU2R'U'RUR'**</span>
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:5678,edge:5678,center:123456,monitorCorner:8,cornerDirAndPath:84,formula:RU2R'U'RUR'}
" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

You may encounter the situation where the target corner block is already at the bottom. you has no way to turn it to the UFR position. You can use any of the formulas described above to push the bottom corner block to the top layer and then it become one of the case1-3.<BR>

So far, you have learned 3 of the 9 formulas, and you can restore the Rubik's cube by learning 6 formulas. :)
