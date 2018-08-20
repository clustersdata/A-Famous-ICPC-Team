# A-Famous-ICPC-Team
A Famous ICPC Team
描述
Mr. B, Mr. G, Mr. M and their coach Professor S are planning their way to Warsaw for the ACM-ICPC World Finals. Each of the four has a square-shaped suitcase with side length Ai (1<=i<=4) respectively. They want to pack their suitcases into a large square box. The heights of the large box as well as the four suitcases are exactly the same. So they only need to consider the large box’s side length. Of course, you should write a program to output the minimum side length of the large box, so that the four suitcases can be put into the box without overlapping.
输入
Each test case contains only one line containing 4 integers Ai (1<=i<=4, 1<=Ai<=1,000,000,000) indicating the side length of each suitcase.
输出
For each test case, display a single line containing the case number and the minimum side length of the large box required.
样例输入
2 2 2 2
2 2 2 1
样例输出
Case 1: 4
Case 2: 4
提示
For the first case, all suitcases have size 2x2. So they can perfectly be packed in 
a 4x4 large box without wasting any space.
For the second case, three suitcases have size 2x2 and the last one is 1x1. No
matter how you rotate or move the suitcases, the side length of the large box must
be at least 4.
