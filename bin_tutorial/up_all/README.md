###  Solve all yellow on the up layer
Through the previous step you have got a up cross, this step your goal is to restore the entire top yellow color, your goal:
<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.0,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U}}
" width="100px" height="100px" frameborder="0" scrolling="no"></iframe>

This step only requires 1 formula <span style="color: red;">**RUR'URU2R'**</span>. For details, please refer to the illustration.


- Case1 There is a special small fish pattern on the up. Put the fish head in the UFL(up front left) position. Note that the yellow color of UFR(up front right) is towards front. This fish is a valid small fish. Use following formula will get the complete up yellow.

<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:<2<3<4,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case2 There is a special invalid fish on the up, put the fish head in the UFL (up front left) position,  Note that the yellow color of UFR(up front right) is towards right, this fish is a invalid small fish, use the following formula can get valid small fish(Case1),which becomes Case1, and uses the Case1 method to get the complete up yellow.

<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:>2<3<3>4,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case3 There is a cross on the U(up), the yellow color of the UFL(up front left) is toward the left, and the yellow of the UFR(up front right) is toward the right. As shown in the figure below, you can get a valid up small fish with this formula, which becomes Case1, and uses the Case1 method to get the complete up yellow.

<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:<2>3>4,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case4 The yellow color of the 2 corner blocks on the up layer is wrong. The yellow color of UFL(up front left) is toward left and the yellow color of UBL(up back left) is toward left. In this case, you can use this formula to convert to Case3, and uses the Case3 method to get the complete up yellow.

<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:>2,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case5 The yellow color of the 2 corner blocks on the up layer is wrong. The yellow color of UFL(up front left) is toward front, and the yellow color of the UBL(up back left) is toward back. This situation is very similar to Case4. After using this formula, you can change to Case2 ( invalid small fish), and uses the Case2 method to get the complete up yellow.

<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:<2,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

- Case6 The yellow color of the 2 corner blocks on the up layer is wrong. The yellow color of UFL(up front left) is toward left, and the yellow color of the UBR(up back right) is toward back. After using this formula, you can change to Case3, and uses the Case3 method to get the complete up yellow.

<iframe src="https://fy-create.github.io/Cube/tools/browser/cube.html?para={screenRatio:1.5,eye:true,corner:12345678,edge:1234567890AB,center:123456,edgeValidFace:{1:U,2:U,3:U,4:U},cornerValidFace:{1:U,2:U,3:U,4:U},cornerDirAndPath:>3,formula:RUR'URU2R'}" width="300px" height="300px" frameborder="0" scrolling="no"></iframe>

The key of this step is to use <span style="color: red;">**RUR'URU2R'**</span> to get a <span style="color: red;">**valid small fish**</span> at the up face according to the up situation, and then use this formula to get the complete up yellow.

So far, you have learned 7 of the 9 formulas, and you can restore the Rubik's cube by learning 2 formulas. :)
<p style="color: #5e9ca0;"><span style="background-color: #ff0000;"><span style="background-color: #00ff00;">&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>&nbsp;&nbsp;</span> 7/9</p>
