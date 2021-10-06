# Programming&nbspAssignment:&nbspLinear&nbspRegression

## ex1

Diagonal&nbspMatrix<br>

&nbsp&nbsp&nbsp1&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp<br>
&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp1&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0<br>
&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp1&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0<br>
&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp1&nbsp&nbsp&nbsp0<br>
&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp0&nbsp&nbsp&nbsp1<br>

Program&nbsppaused.&nbspPress&nbspenter&nbspto&nbspcontinue.<br>
Plotting&nbspData&nbsp...<br>

![image-20211006175846009](./pic/image-20211006175846009.png)

Program&nbsppaused.&nbspPress&nbspenter&nbspto&nbspcontinue.<br>

Testing&nbspthe&nbspcost&nbspfunction&nbsp...<br><br>
With&nbsptheta&nbsp=&nbsp[0&nbsp;&nbsp0]<br>
Cost&nbspcomputed&nbsp=&nbsp32.072734<br>
Expected&nbspcost&nbspvalue&nbsp(approx)&nbsp32.07<br>

With&nbsptheta&nbsp=&nbsp[-1&nbsp;&nbsp2]<br>
Cost&nbspcomputed&nbsp=&nbsp54.242455<br>
Expected&nbspcost&nbspvalue&nbsp(approx)&nbsp54.24<br>
Program&nbsppaused.&nbspPress&nbspenter&nbspto&nbspcontinue.<br>

Running&nbspGradient&nbspDescent&nbsp...<br>
Theta&nbspfound&nbspby&nbspgradient&nbspdescent:<br>
-3.630291<br>
1.166362<br>
Expected&nbsptheta&nbspvalues&nbsp(approx)<br>
&nbsp-3.6303<br>
&nbsp&nbsp1.1664<br>

For&nbsppopulation&nbsp=&nbsp35,000,&nbspwe&nbsppredict&nbspa&nbspprofit&nbspof&nbsp4519.767868<br>
For&nbsppopulation&nbsp=&nbsp70,000,&nbspwe&nbsppredict&nbspa&nbspprofit&nbspof&nbsp45342.450129<br>
Program&nbsppaused.&nbspPress&nbspenter&nbspto&nbspcontinue.<br>

Visualizing&nbspJ(theta_0,&nbsptheta_1)&nbsp...<br>

![image-20211006180021220](./pic/image-20211006180021220.png)

![image-20211006180044253](./pic/image-20211006180044253.png)

![image-20211006180053458](./pic/image-20211006180053458.png)

## ex1_mulit&nbsp

&nbspLoading&nbspdata&nbsp...<br>
First&nbsp10&nbspexamples&nbspfrom&nbspthe&nbspdataset:<br>
&nbspx&nbsp=&nbsp[2104&nbsp3],&nbspy&nbsp=&nbsp399900<br>
&nbspx&nbsp=&nbsp[1600&nbsp3],&nbspy&nbsp=&nbsp329900<br>
&nbspx&nbsp=&nbsp[2400&nbsp3],&nbspy&nbsp=&nbsp369000<br>
&nbspx&nbsp=&nbsp[1416&nbsp2],&nbspy&nbsp=&nbsp232000<br>
&nbspx&nbsp=&nbsp[3000&nbsp4],&nbspy&nbsp=&nbsp539900<br>
&nbspx&nbsp=&nbsp[1985&nbsp4],&nbspy&nbsp=&nbsp299900<br>
&nbspx&nbsp=&nbsp[1534&nbsp3],&nbspy&nbsp=&nbsp314900<br>
&nbspx&nbsp=&nbsp[1427&nbsp3],&nbspy&nbsp=&nbsp198999<br>
&nbspx&nbsp=&nbsp[1380&nbsp3],&nbspy&nbsp=&nbsp212000<br>
&nbspx&nbsp=&nbsp[1494&nbsp3],&nbspy&nbsp=&nbsp242500<br>
Program&nbsppaused.&nbspPress&nbspenter&nbspto&nbspcontinue.<br>
Normalizing&nbspFeatures&nbsp...<br>
Running&nbspgradient&nbspdescent&nbsp...<br>

![image-20211006185535408](./pic/image-20211006185535408.png)
Theta&nbspcomputed&nbspfrom&nbspgradient&nbspdescent:<br>
&nbsp334302.063993<br>
&nbsp100087.116006<br>
&nbsp3673.548451<br>

Predicted&nbspprice&nbspof&nbspa&nbsp1650&nbspsq-ft,&nbsp3&nbspbr&nbsphouse&nbsp(using&nbspgradient&nbspdescent):<br>
&nbsp$289314.620338<br>
Program&nbsppaused.&nbspPress&nbspenter&nbspto&nbspcontinue.<br>
Solving&nbspwith&nbspnormal&nbspequations...<br>
Theta&nbspcomputed&nbspfrom&nbspthe&nbspnormal&nbspequations:<br>
&nbsp89597.909543<br>
&nbsp139.210674<br>
&nbsp-8738.019112<br>

Predicted&nbspprice&nbspof&nbspa&nbsp1650&nbspsq-ft,&nbsp3&nbspbr&nbsphouse&nbsp(using&nbspnormal&nbspequations):<br>
&nbsp$293081.464335<br>



## submit&nbspresult

==
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspPart&nbspName&nbsp|&nbsp&nbsp&nbsp&nbsp&nbspScore&nbsp|&nbspFeedback
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp---------&nbsp|&nbsp&nbsp&nbsp&nbsp&nbsp-----&nbsp|&nbsp--------
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspWarm-up&nbspExercise&nbsp|&nbsp&nbsp10&nbsp/&nbsp&nbsp10&nbsp|&nbspNice&nbspwork!
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspComputing&nbspCost&nbsp(for&nbspOne&nbspVariable)&nbsp|&nbsp&nbsp40&nbsp/&nbsp&nbsp40&nbsp|&nbspNice&nbspwork!
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspGradient&nbspDescent&nbsp(for&nbspOne&nbspVariable)&nbsp|&nbsp&nbsp50&nbsp/&nbsp&nbsp50&nbsp|&nbspNice&nbspwork!
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspFeature&nbspNormalization&nbsp|&nbsp&nbsp&nbsp0&nbsp/&nbsp&nbsp&nbsp0&nbsp|&nbspNice&nbspwork!
==&nbsp&nbsp&nbsp&nbsp&nbspComputing&nbspCost&nbsp(for&nbspMultiple&nbspVariables)&nbsp|&nbsp&nbsp&nbsp0&nbsp/&nbsp&nbsp&nbsp0&nbsp|&nbspNice&nbspwork!
==&nbsp&nbsp&nbspGradient&nbspDescent&nbsp(for&nbspMultiple&nbspVariables)&nbsp|&nbsp&nbsp&nbsp0&nbsp/&nbsp&nbsp&nbsp0&nbsp|&nbspNice&nbspwork!
==&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspNormal&nbspEquations&nbsp|&nbsp&nbsp&nbsp0&nbsp/&nbsp&nbsp&nbsp0&nbsp|&nbspNice&nbspwork!
