dvisual
===

dvisual is a visualization toolkit based on html's canvas and Javascript


----------------------------------------------
Code Files
===

`./dv.js` -the main js file

`./test.html` -the test html file

----------------------------------------------
<script type="text/javascript" src="dv.js">
</script>
<script type="text/javascript" src="https://raw.githubusercontent.com/justdark/dvisual/master/dv.js
">
</script>
Examples（TODO）
===
<canvas id="PieCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var pietest = new DVcanvas("PieCanvas");
pietest.DrawPie(["Mon","Tus","Wend","Friday"],[2,3,6,8]);
</script>

<img src="./image/1.png" alt="Drawing" width="400px" />

----------------------------------------------
<canvas id="MulBarCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var test3 = new DVcanvas("MulBarCanvas");
test3.drawAxes(0,0,"","高度");
test3.DrawMulBar(["Today","Tomm","Sam","BBBBBBBB"],[[12,2,4],[4,2,7],[6,3,9],[15,13,5]],["TTT","BBB","QQQQQ"]);
</script>
<img src="./image/2.png" alt="Drawing" width="400px" />

----------------------------------------------
<canvas id="BarCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var test2 = new DVcanvas("BarCanvas");
test2.drawAxes(0,0);
test2.DrawBar(["Today","Tomm","Sam","BBBBBBBB"],[12,4,6,15]);
</script>
<img src="./image/3.png" alt="Drawing" width="400px" />

----------------------------------------------


<canvas id="linePathCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var linePathTest = new DVcanvas("linePathCanvas");
linePathTest.drawAxes(0,0);
linePathTest.linePath([0.0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.6, 2.7, 2.8, 2.9, 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 5.0, 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0, 6.1, 6.2, 6.3, 6.4, 6.5, 6.6, 6.7, 6.8, 6.9, 7.0, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 7.9, 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.6, 8.7, 8.8, 8.9, 9.0, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9],[10.0, 9.604000000000003, 9.216, 8.836000000000002, 8.463999999999999, 8.1, 7.744000000000001, 7.395999999999999, 7.056, 6.724, 6.4, 6.084, 5.776, 5.476, 5.184000000000001, 4.9, 4.624, 4.356, 4.096000000000001, 3.8440000000000003, 3.6, 3.364, 3.1359999999999997, 2.9160000000000004, 2.704, 2.5, 2.304, 2.1159999999999997, 1.9360000000000002, 1.764, 1.6, 1.444, 1.2959999999999996, 1.1560000000000001, 1.0240000000000002, 0.9, 0.7839999999999999, 0.6759999999999998, 0.5760000000000002, 0.48400000000000004, 0.4, 0.3240000000000003, 0.2559999999999999, 0.19600000000000012, 0.14399999999999985, 0.1, 0.06400000000000011, 0.03599999999999996, 0.016000000000000028, 0.0039999999999999715, 0.0, 0.0039999999999999715, 0.016000000000000028, 0.03599999999999996, 0.06400000000000011, 0.1, 0.14399999999999985, 0.19600000000000012, 0.2559999999999999, 0.3240000000000003, 0.4, 0.4839999999999997, 0.5760000000000002, 0.6759999999999998, 0.7840000000000005, 0.9, 1.0239999999999996, 1.1560000000000001, 1.2959999999999996, 1.4440000000000004, 1.6, 1.7639999999999991, 1.9360000000000002, 2.1159999999999997, 2.3040000000000007, 2.5, 2.7039999999999993, 2.9160000000000004, 3.1359999999999997, 3.3640000000000008, 3.6, 3.8439999999999994, 4.095999999999998, 4.356000000000002, 4.6240000000000006, 4.9, 5.183999999999998, 5.475999999999998, 5.776000000000002, 6.0840000000000005, 6.4, 6.724, 7.0559999999999965, 7.396000000000003, 7.744000000000001, 8.1, 8.463999999999999, 8.835999999999997, 9.216000000000003, 9.604000000000003],'#F00');
</script>
<img src="./image/4.png" alt="Drawing" width="400px" />


----------------------------------------------
<canvas id="DotPathCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var DotPathTest = new DVcanvas("DotPathCanvas");
DotPathTest.drawAxes(0,0);
DotPathTest.DotPath([0.0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.6, 2.7, 2.8, 2.9, 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 5.0, 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0, 6.1, 6.2, 6.3, 6.4, 6.5, 6.6, 6.7, 6.8, 6.9, 7.0, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 7.9, 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.6, 8.7, 8.8, 8.9, 9.0, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9],[10.0, 9.604000000000003, 9.216, 8.836000000000002, 8.463999999999999, 8.1, 7.744000000000001, 7.395999999999999, 7.056, 6.724, 6.4, 6.084, 5.776, 5.476, 5.184000000000001, 4.9, 4.624, 4.356, 4.096000000000001, 3.8440000000000003, 3.6, 3.364, 3.1359999999999997, 2.9160000000000004, 2.704, 2.5, 2.304, 2.1159999999999997, 1.9360000000000002, 1.764, 1.6, 1.444, 1.2959999999999996, 1.1560000000000001, 1.0240000000000002, 0.9, 0.7839999999999999, 0.6759999999999998, 0.5760000000000002, 0.48400000000000004, 0.4, 0.3240000000000003, 0.2559999999999999, 0.19600000000000012, 0.14399999999999985, 0.1, 0.06400000000000011, 0.03599999999999996, 0.016000000000000028, 0.0039999999999999715, 0.0, 0.0039999999999999715, 0.016000000000000028, 0.03599999999999996, 0.06400000000000011, 0.1, 0.14399999999999985, 0.19600000000000012, 0.2559999999999999, 0.3240000000000003, 0.4, 0.4839999999999997, 0.5760000000000002, 0.6759999999999998, 0.7840000000000005, 0.9, 1.0239999999999996, 1.1560000000000001, 1.2959999999999996, 1.4440000000000004, 1.6, 1.7639999999999991, 1.9360000000000002, 2.1159999999999997, 2.3040000000000007, 2.5, 2.7039999999999993, 2.9160000000000004, 3.1359999999999997, 3.3640000000000008, 3.6, 3.8439999999999994, 4.095999999999998, 4.356000000000002, 4.6240000000000006, 4.9, 5.183999999999998, 5.475999999999998, 5.776000000000002, 6.0840000000000005, 6.4, 6.724, 7.0559999999999965, 7.396000000000003, 7.744000000000001, 8.1, 8.463999999999999, 8.835999999999997, 9.216000000000003, 9.604000000000003],'#F00');
</script>
<img src="./image/5.png" alt="Drawing" width="400px" />

----------------------------------------------
<canvas id="MulLinePathCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var test7 = new DVcanvas("MulLinePathCanvas");
test7.drawAxes(0,0,"天气","号码sssssssssss");
test7.MulLinePath([[0.0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.6, 2.7, 2.8, 2.9, 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 5.0, 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0, 6.1, 6.2, 6.3, 6.4, 6.5, 6.6, 6.7, 6.8, 6.9, 7.0, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 7.9, 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.6, 8.7, 8.8, 8.9, 9.0, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9],[0.0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.6, 2.7, 2.8, 2.9, 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 5.0, 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0, 6.1, 6.2, 6.3, 6.4, 6.5, 6.6, 6.7, 6.8, 6.9, 7.0, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 7.9, 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.6, 8.7, 8.8, 8.9, 9.0, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9],[0,10]],[[10.0, 9.604000000000003, 9.216, 8.836000000000002, 8.463999999999999, 8.1, 7.744000000000001, 7.395999999999999, 7.056, 6.724, 6.4, 6.084, 5.776, 5.476, 5.184000000000001, 4.9, 4.624, 4.356, 4.096000000000001, 3.8440000000000003, 3.6, 3.364, 3.1359999999999997, 2.9160000000000004, 2.704, 2.5, 2.304, 2.1159999999999997, 1.9360000000000002, 1.764, 1.6, 1.444, 1.2959999999999996, 1.1560000000000001, 1.0240000000000002, 0.9, 0.7839999999999999, 0.6759999999999998, 0.5760000000000002, 0.48400000000000004, 0.4, 0.3240000000000003, 0.2559999999999999, 0.19600000000000012, 0.14399999999999985, 0.1, 0.06400000000000011, 0.03599999999999996, 0.016000000000000028, 0.0039999999999999715, 0.0, 0.0039999999999999715, 0.016000000000000028, 0.03599999999999996, 0.06400000000000011, 0.1, 0.14399999999999985, 0.19600000000000012, 0.2559999999999999, 0.3240000000000003, 0.4, 0.4839999999999997, 0.5760000000000002, 0.6759999999999998, 0.7840000000000005, 0.9, 1.0239999999999996, 1.1560000000000001, 1.2959999999999996, 1.4440000000000004, 1.6, 1.7639999999999991, 1.9360000000000002, 2.1159999999999997, 2.3040000000000007, 2.5, 2.7039999999999993, 2.9160000000000004, 3.1359999999999997, 3.3640000000000008, 3.6, 3.8439999999999994, 4.095999999999998, 4.356000000000002, 4.6240000000000006, 4.9, 5.183999999999998, 5.475999999999998, 5.776000000000002, 6.0840000000000005, 6.4, 6.724, 7.0559999999999965, 7.396000000000003, 7.744000000000001, 8.1, 8.463999999999999, 8.835999999999997, 9.216000000000003, 9.604000000000003],[1.25, 1.2005000000000003, 1.152, 1.1045000000000003, 1.0579999999999998, 1.0125, 0.9680000000000002, 0.9244999999999999, 0.882, 0.8404999999999999, 0.8, 0.7605, 0.722, 0.6845000000000001, 0.648, 0.6125, 0.578, 0.5445, 0.5120000000000001, 0.48050000000000004, 0.45, 0.4205, 0.39199999999999996, 0.36450000000000005, 0.338, 0.3125, 0.288, 0.26449999999999996, 0.24200000000000005, 0.2205, 0.2, 0.1805, 0.16199999999999998, 0.14450000000000002, 0.12800000000000003, 0.1125, 0.09799999999999999, 0.08449999999999998, 0.07200000000000002, 0.06050000000000001, 0.05, 0.04050000000000003, 0.03199999999999999, 0.024500000000000015, 0.01799999999999998, 0.0125, 0.008000000000000014, 0.004499999999999995, 0.0020000000000000035, 0.0004999999999999964, 0.0, 0.0004999999999999964, 0.0020000000000000035, 0.004499999999999995, 0.008000000000000014, 0.0125, 0.01799999999999998, 0.024500000000000015, 0.03199999999999999, 0.04050000000000003, 0.05, 0.060499999999999964, 0.07200000000000002, 0.08449999999999998, 0.09800000000000006, 0.1125, 0.12799999999999995, 0.14450000000000002, 0.16199999999999998, 0.18050000000000005, 0.2, 0.22049999999999992, 0.24200000000000005, 0.26449999999999996, 0.2880000000000001, 0.3125, 0.3379999999999999, 0.36450000000000005, 0.39199999999999996, 0.4205000000000001, 0.45, 0.48049999999999987, 0.5119999999999998, 0.5445000000000002, 0.5780000000000001, 0.6125, 0.6479999999999999, 0.6844999999999997, 0.7220000000000002, 0.7605000000000002, 0.8, 0.8404999999999999, 0.8819999999999997, 0.9245000000000003, 0.9680000000000002, 1.0125, 1.0579999999999998, 1.1044999999999996, 1.1520000000000004, 1.2005000000000003],[0,10]],["Line1","Lisssssssne2","sssss"],0,0);
</script>
<img src="./image/6.png" alt="Drawing" width="400px" />

----------------------------------------------

<canvas id="HistCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var test4 = new DVcanvas("HistCanvas");
test4.drawAxes(0,0);
//test4.DrawHist([1,2,3,4,5,6,7,8,9,0,2,3,4,5,6,7,8,9,3,4,5,6,7,4,5,6,4,4,5,6],0,1);
test4.DrawHist([4.845526425588935, 4.259344936827764, 3.8098053040235538, 1.952000211472447, 4.635797415383389, 4.024019790968537, 3.3602908242946734, 5.904528760874355, 4.198898591038685, 3.590128975916881, 4.332713128186926, 3.1865396813511784, 2.5162865661667198, 4.712821025260148, 3.71360994330834, 3.8493524061913744, 3.7159258918857536, 5.51399789047954, 3.6300232108929382, 3.545076471891732, 3.0676446553817147, 3.2444930114999093, 3.5479330646839933, 4.976746738515327, 3.9332813190873934, 5.006312033998867, 3.404727953308918, 3.5033407619438233, 3.079551989356432, 3.8632840581876042, 3.157986089467415, 3.4195326824382866, 3.8080356643280124, 2.957309227091329, 4.118392736251364, 3.6411410599078917, 3.7624757886685964, 4.8647889699576226, 5.21796736714372, 3.976067213322964, 5.126928746440573, 3.974656703704623, 3.233580498913617, 4.395312593899124, 4.068962687058488, 3.891929789953702, 4.469243993566407, 4.334454703693426, 3.9209889294562856, 3.4434304992247453, 4.497549493028219, 3.416343894896489, 4.665283209646114, 4.680609105269387, 4.983997832840491, 3.6712180044043317, 3.265064804033842, 3.4698542145767295, 3.600410757683259, 3.258705331315113, 3.4711330714824475, 5.850035283124024, 4.4280162444420395, 2.9032881754752737, 3.8438971175165753, 4.876106607781984, 2.558687703308084, 3.5013932005344044, 3.5555419525521454, 5.1907150725045845, 4.011722379620389, 3.527897189378135, 4.10495828533477, 6.62176464809461, 4.2726902430636144, 3.900071148628866, 2.575252541466217, 5.328266087881893, 2.5589399335225336, 5.724120236174612, 4.4515392634560085, 4.7151321389757594, 2.8531894976428953, 3.4703243319242265, 2.2640882905146724, 5.0719845838182795, 3.574145032952119, 4.477360695988922, 5.779618114520955, 4.456319741265055, 3.8274174274387756, 6.050865845999171, 5.286157426108568, 4.197556181625366, 3.2386132037552726, 4.409816073319034, 4.225877761979799, 5.313407146149141, 5.042124222577709, 3.979632468039347],0,0.5);
</script>
<img src="./image/7.png" alt="Drawing" width="400px" />

----------------------------------------------

<canvas id="RadarCanvas" height="300px" width ="400px"></canvas>
<script type="text/javascript">
var test6 = new DVcanvas("RadarCanvas");

//test4.DrawHist([1,2,3,4,5,6,7,8,9,0,2,3,4,5,6,7,8,9,3,4,5,6,7,4,5,6,4,4,5,6],0,1);
test6.DrawRadar(["型号1","型号2"],[[6,7,3,5,6],[3,6,7,2,8]],["速度","能力","强度","战斗力","成本"],0,10);
<img src="./image/8.png" alt="Drawing" width="400px" />

</script>


----------------------------------------------
Class Format Guid
===
TODO

----------------------------------------------
Install
===
just use the `dv.js` as usual

----------------------------------------------
Warning
===
All code have been tested on Chrome（both retina display and ordinary display)

----------------------------------------------
License
===
[WTFPL](http://www.wtfpl.net/)
