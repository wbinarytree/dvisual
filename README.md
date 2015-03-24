dvisual
===

dvisual is a visualization toolkit based on html's canvas and Javascript

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/example.png" alt="Drawing" width="700px" />

----------------------------------------------
Code Files
===

`./dvisual.js` -the main js file

`./example.html` -the test html file

----------------------------------------------
How to use DVisual
===
[The Tutorial](https://github.com/justdark/dvisual/blob/master/tutorial.md)

[API document](http://justdark.github.io/dvisual/doc/)

[DVisualMap Tutorial](https://github.com/justdark/dvisual/blob/master/dvmap/dvmap_tutorial.md)

----------------------------------------------
<script type="text/javascript" src="dv.js">
</script>
<script type="text/javascript" src="https://raw.githubusercontent.com/justdark/dvisual/master/dv.js
">
</script>
Examples
===

	dvisual = new DVisual("myCanvas");
	args = {'X':["星期一","星期二","星期三","星期四","星期五","周六","周末"],'stackedClass':["吃饭","读书","睡觉"],'stackedY':[[2,3,6],[3,4,3],[5,3,2],[4,4,1],[2,3,5],[3,3,3],[4,2,4]],'all':1,'index':1,'style':'stacked','stackedColor':[new DVColor(55,185,241,0.5),new DVColor(207,231,62,0.5),new DVColor(216,121,121,0.5)]}
	
	dvisual.addElement(new DVBarChart(args));
	dvisual.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/1.png" alt="Drawing" width="400px" />

----------------------------------------------

	args = {'Xs':[[1,2,3,4,5,6,7,8],[0,1,2,3,4,5,6,7,8,9]],
		'Ys':[[1,2,3,4,5,6,7,8],[3,4,3,5,6,7,8,8,9,8]],
		'classes':["AAA","BBB"],
		'style':'dot|area'}
	dvisual = new DVisual("myCanvas1");
	dvisual.addElement(new DVMulLineChart(args));
	dvisual.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/2.png" alt="Drawing" width="400px" />

----------------------------------------------

	args = {'X':["A",'B','C'],'Ys':[[3,2,4],[5,7,8],[9,3,1]],
		'Z':["first","secossnd","third"]}
	dvisual = new DVisual("myCanvas2");
	dvisual.addElement(new DVMulBarChart(args));
	dvisual.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/3.png" alt="Drawing" width="400px" />

----------------------------------------------

	args = {'X':[1,2,3,4,5,6],'Y':[1,2,3,4,5,6],
			'bubbleRadius':[1,2,3,4,5,6],'style':'bubble'}
	dvisual = new DVisual("myCanvas3");
	dvisual.addElement(new DVLineChart(args));
	dvisual.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/4.png" alt="Drawing" width="400px" />

----------------------------------------------

	args = {'Xs':[[1,2,3,4,5,6],[1,2,3,4,5,6]],'Ys':[[1,2,3,4,3,6],[3,5,2,7,5,2]],
			'classes':['A','B'],'style':'dot|line'}
	dvisual = new DVisual("myCanvas4");
	dvisual.addElement(new DVMulLineChart(args));
	dvisual.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/5.png" alt="Drawing" width="400px" />

----------------------------------------------

	arhs = {'X':[4.845526425588935, 4.259344936827764, 3.8098053040235538, 1.952000211472447, 4.635797415383389, 4.024019790968537, 3.3602908242946734, 5.904528760874355, 4.198898591038685, 3.590128975916881, 4.332713128186926, 3.1865396813511784, 2.5162865661667198, 4.712821025260148, 3.71360994330834, 3.8493524061913744, 3.7159258918857536, 5.51399789047954, 3.6300232108929382, 3.545076471891732, 3.0676446553817147, 3.2444930114999093, 3.5479330646839933, 4.976746738515327, 3.9332813190873934, 5.006312033998867, 3.404727953308918, 3.5033407619438233, 3.079551989356432, 3.8632840581876042, 3.157986089467415, 3.4195326824382866, 3.8080356643280124, 2.957309227091329, 4.118392736251364, 3.6411410599078917, 3.7624757886685964, 4.8647889699576226, 5.21796736714372, 3.976067213322964, 5.126928746440573, 3.974656703704623, 3.233580498913617, 4.395312593899124, 4.068962687058488, 3.891929789953702, 4.469243993566407, 4.334454703693426, 3.9209889294562856, 3.4434304992247453, 4.497549493028219, 3.416343894896489, 4.665283209646114, 4.680609105269387, 4.983997832840491, 3.6712180044043317, 3.265064804033842, 3.4698542145767295, 3.600410757683259, 3.258705331315113, 3.4711330714824475, 5.850035283124024, 4.4280162444420395, 2.9032881754752737, 3.8438971175165753, 4.876106607781984, 2.558687703308084, 3.5013932005344044, 3.5555419525521454, 5.1907150725045845, 4.011722379620389, 3.527897189378135, 4.10495828533477, 6.62176464809461, 4.2726902430636144, 3.900071148628866, 2.575252541466217, 5.328266087881893, 2.5589399335225336, 5.724120236174612, 4.4515392634560085, 4.7151321389757594, 2.8531894976428953, 3.4703243319242265, 2.2640882905146724, 5.0719845838182795, 3.574145032952119, 4.477360695988922, 5.779618114520955, 4.456319741265055, 3.8274174274387756, 6.050865845999171, 5.286157426108568, 4.197556181625366, 3.2386132037552726, 4.409816073319034, 4.225877761979799, 5.313407146149141, 5.042124222577709, 3.979632468039347],'yStyle':'percentage','sec':0.5};
	
	dvisual = new DVisual('myCanvas5')
	dvisual.addElement(new DVHistChart(args))
	dvisual.draw()

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/6.png" alt="Drawing" width="400px" />

----------------------------------------------

	args = {'Xs':[[1,-2,3,4,5,6],[1,2,3,4,5,6]],'Ys':[[1,2,3,4,3,6],[-3,5,2,7,5,2]],
		'Zs':[[3,2,1,4,5,7],[3,2,7,6,8,4]],'classes':['A','B'],'style':'bubble'}
		
	dvisual = new DVisual("myCanvas6");
	dvisual.addElement(new DVMulLineChart(args));
	dvisual.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/7.png" alt="Drawing" width="400px" />

----------------------------------------------

	args = {'X':[0.0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.6, 2.7, 2.8, 2.9, 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 5.0, 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0, 6.1, 6.2, 6.3, 6.4, 6.5, 6.6, 6.7, 6.8, 6.9, 7.0, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 7.9, 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.6, 8.7, 8.8, 8.9, 9.0, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9,10],'Y':[9.13090620029994, 7.118300004364756, 8.64075587951997, 9.710416441115218, 9.322846742922088, 9.056150136621335, 9.108101564537487, 8.45509698625086, 8.736924245835883, 7.606032672634812, 8.472099236483583, 9.649924244748698, 5.489023620765848, 6.690238017789536, 8.927546999917414, 9.111519664637672, 5.904779569425021, 6.780722878295234, 9.945332217015842, 7.501304076985086, 6.082375428413196, 6.57377277146206, 8.274120012523575, 8.515875409971441, 6.299972235660604, 5.340470072916613, 9.28998344449515, 6.188764358552173, 6.182738909396689, 8.67827861163249, 7.07119639776137, 9.889709178650673, 6.290422354938657, 7.046146905262395, 6.23061670372797, 6.317085843673329, 8.309873819045226, 5.575082261697132, 6.307515915568937, 5.547239649724286, 7.305925134529345, 8.746560085903551, 5.533181502797484, 9.761626578912853, 8.923356053583273, 7.985761119072953, 5.737691237086597, 5.8199601865342405, 7.759143636641751, 6.1896422735808265, 7.6918797363317895, 5.811659272940641, 7.996245645380639, 6.3542735782532365, 9.482769458131678, 6.256515633074864, 9.1189471069112, 7.042961732062109, 7.3515458801854106, 5.714510448941691, 7.448124222844859, 7.438814924844461, 5.978770753259722, 8.092623691039387, 6.630849003048162, 8.060724433470916, 5.119396558625851, 9.72884812447111, 9.841723919560728, 6.710031704591236, 6.73252767860526, 6.897608624985936, 5.9542512922369015, 5.3824047839578455, 9.643712606643193, 7.18175836750534, 8.646294410555333, 8.217995263080937, 6.480223580707265, 9.110910334369457, 8.562243378764022, 8.56430945969737, 6.885171824616584, 5.1601746219124065, 6.651662757371544, 8.1564707951565, 5.691161264861341, 5.111805073632494, 7.528182442056384, 5.078872201678394, 5.935293490691965, 8.088370241340872, 5.137356502438488, 7.090546858086129, 7.178951275165159, 6.8952735922524635, 9.493715613322806, 6.563386553133646, 8.684211353694348, 8.267582158760106,5.6],
		'style':'area|dot'}

	dvisual = new DVisual("myCanvas7");
	dvisual.addElement(new DVLineChart(args));
	dvisual.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/8.png" alt="Drawing" width="400px" />

----------------------------------------------

	singline = {'X':[0.0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2.0, 2.1, 2.2, 2.3, 2.4, 2.5, 2.6, 2.7, 2.8, 2.9, 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 5.0, 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0, 6.1, 6.2, 6.3, 6.4, 6.5, 6.6, 6.7, 6.8, 6.9, 7.0, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 7.9, 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.6, 8.7, 8.8, 8.9, 9.0, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9,10],'Y':[10.0, 9.604000000000003, 9.216, 8.836000000000002, 8.463999999999999, 8.1, 7.744000000000001, 7.395999999999999, 7.056, 6.724, 6.4, 6.084, 5.776, 5.476, 5.184000000000001, 4.9, 4.624, 4.356, 4.096000000000001, 3.8440000000000003, 3.6, 3.364, 3.1359999999999997, 2.9160000000000004, 2.704, 2.5, 2.304, 2.1159999999999997, 1.9360000000000002, 1.764, 1.6, 1.444, 1.2959999999999996, 1.1560000000000001, 1.0240000000000002, 0.9, 0.7839999999999999, 0.6759999999999998, 0.5760000000000002, 0.48400000000000004, 0.4, 0.3240000000000003, 0.2559999999999999, 0.19600000000000012, 0.14399999999999985, 0.1, 0.06400000000000011, 0.03599999999999996, 0.016000000000000028, 0.0039999999999999715, 0.0, 0.0039999999999999715, 0.016000000000000028, 0.03599999999999996, 0.06400000000000011, 0.1, 0.14399999999999985, 0.19600000000000012, 0.2559999999999999, 0.3240000000000003, 0.4, 0.4839999999999997, 0.5760000000000002, 0.6759999999999998, 0.7840000000000005, 0.9, 1.0239999999999996, 1.1560000000000001, 1.2959999999999996, 1.4440000000000004, 1.6, 1.7639999999999991, 1.9360000000000002, 2.1159999999999997, 2.3040000000000007, 2.5, 2.7039999999999993, 2.9160000000000004, 3.1359999999999997, 3.3640000000000008, 3.6, 3.8439999999999994, 4.095999999999998, 4.356000000000002, 4.6240000000000006, 4.9, 5.183999999999998, 5.475999999999998, 5.776000000000002, 6.0840000000000005, 6.4, 6.724, 7.0559999999999965, 7.396000000000003, 7.744000000000001, 8.1, 8.463999999999999, 8.835999999999997, 9.216000000000003, 9.604000000000003,10],'style':'dot'}

	sl = new DVisual("myCanvas8");
	sl.addElement(new DVLineChart(singline));
	sl.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/9.png" alt="Drawing" width="400px" />

----------------------------------------------

	dvisual = new DVisual("myCanvas9");

	dvisual.addElement(new DVPieChart({'X':["星期一","星期二","星期四","周末"],'Y':[2,3,4,5]}))
	dvisual.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/10.png" alt="Drawing" width="400px" />

----------------------------------------------

	dvisual = new DVisual("myCanvas10");
	dvisual.addElement(new DVRadarChart({'X':["型号1","型号2"],'Y':[[6,7,3,5,6,9],[8,6,7,2,8,6]],'arguments':["速度","能力","强度","战斗力","成本","价格"]}))
	dvisual.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/11.png" alt="Drawing" width="400px" />

----------------------------------------------

	sbar = new DVisual("myCanvas11");
	sbar.addElement(new DVBarChart({'X':["Today","Tomm","Sam","BBBBBBBB"],'Y':[5,9,4,8]}))
	sbar.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/12.png" alt="Drawing" width="400px" />


----------------------------------------------

	s13 = new DVisual("myCanvas13");
	s13.addElement(new DVAreaPieChart({'X':["ClassA","ClassB","ClassC","ClassD","ClassE","ClassF"],
										'Y':[2,3,4,5,7,9]}))
	s13.draw()

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/24.png" alt="Drawing" width="400px" />

-----------------------------------------------

	s14 = new DVisual("myCanvas14");
	s14.addElement(new DVBoxChart({'X':["ClassA","ClassB","ClassC"],
										'Ys':[[2,3,4,5,7,9,5,6,2,4,6,7,8,3,5,6,3,2],
											  [5,6,2,4,7,8,3,6,2,7,15,4,8,3,8,9,5,6],
											  [3,2,4,5,6,7,2,12,11,13,12,10,11,15]]}))
	s14.draw()

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/25.png" alt="Drawing" width="400px" />

----------------------------------------------

	s15 = new DVisual("myCanvas15");
	s15.addElement(new DVPieChart({'X':["ClassA","ClassB","ClassC","ClassD"],
										'Y':[2,3,4,5],
										'ring_ratio':0.5}))
	s15.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/26.png" alt="Drawing" width="400px" />

----------------------------------------------

	s16 = new DVisual("myCanvas17");
	s16.addElement(new DVDendrogram({'style':'bubble','tree':[["A",[[["S",[[[[[["A","B"],"B"],"B"],"B"],"B"],"TM"]],"VB"],"ASD"]],["B","C"]]}))
	s16.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/27.png" alt="Drawing" width="400px" />

----------------------------------------------

	s16 = new DVisual("myCanvas18");
	s16.addElement(new DVCircleConnectChart({'nodes':["AAAA","BBBB","CCCC","DDDD","EEEE","FFFF","GGGGGGG","HHHH","IIII","JJJJ","KKKK",'LLLL','MMMM','NNNN','OOOO','PPPP','QQQQ','RRR','SSS','TTT','UUU','VVV','WWW','XXX','YYY','ZZZ',"AAAA","BBBB","CCCC","DDDD","EEEE","FFFF","GGGGGGG","HHHH","IIII","JJJJ","KKKK",'LLLL','MMMM','NNNN','OOOO','PPPP','QQQQ','RRR','SSS','TTT','UUU','VVV','WWW','XXX','YYY','ZZZ']
									,'edges':getMulRandomtuple(51,50) //random edges
									,'bubbleRadius':5
									,'edgesValue':getMulRandomSet(10,50) //random edge value
									,'lineWidth':2
									,'CurveColor':new DVColor(14,110,179)}))
	s16.draw();

<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/28.png" alt="Drawing" width="400px" />

----------------------------------------------

	s19 = new DVisual("myCanvas19");
	s19.addElement(new DVParallelCoordinate({'Xs':getMulRandomMatrix(20,100,5) // random data
										,'arguments':['AAAA','BBBBB','CCCCC','DDDDD','EEEEE'],
										'ColorPattern':[[new DVColor(255,0,0,0.8),	36],[new DVColor(15,38,237,0.8),6]]}));
	s19.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/29.png" alt="Drawing" width="600px" />



----------------------------------------------

	s15 = new DVisual("myCanvas16");
	s15.addElement(new DVGraph({'nodes':["A","B","C","D","E","F","G","H","I","J","K","L","M","Ns","O","P","Q","R","S","T","U","V","W","X","Y","Z"],
							'edges':[[0,1],[1,3],[2,1],[1,4],[1,5],[1,6],[1,7],[1,8],[1,9],[1,10],[1,11],[1,12],[7,13],[3,5],[4,7],[7,2],[7,14],[7,15],[7,16],[1,1],[1,25],[16,17],[16,18],[16,19],[16,20],[20,21],[16,22],[16,23],[16,24],[16,25]],
							'style':'directed',
							'distance':'median',
							'color':new DVColor(111,111,111),
							'ColorPattern':[[new DVColor(255,0,0,1),1,16,7]]}))
	s15.draw();
<img src="https://raw.githubusercontent.com/justdark/dvisual/master/image/30.png" alt="Drawing" width="600px" />

----------------------------------------------
Warning
===
All code have been tested on Chrome（both retina display and ordinary display)

----------------------------------------------
License
===
[WTFPL](http://www.wtfpl.net/)
