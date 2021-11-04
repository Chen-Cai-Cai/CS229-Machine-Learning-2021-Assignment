# Programming Assignment: Support Vector Machines

## ex6

Loading and Visualizing Data ...  
Program paused. Press enter to continue.    

![image-20211030090631208](./pic/image-20211030090631208.png)

Training ......................................................................  
....................................................................... Done!  

Program paused. Press enter to continue.  

![image-20211030090729390](./pic/image-20211030090729390.png)

Evaluating the Gaussian Kernel ...  
Gaussian Kernel between x1 = [1; 2; 1], x2 = [0; 4; -1], sigma = 2.000000 :  
        0.324652  
(for sigma = 2, this value should be about 0.324652)  
Program paused. Press enter to continue.  

 ሀLoading and Visualizing Data ...  
Program paused. Press enter to continue.  

![image-20211030090917991](./pic/image-20211030090917991.png)

Training SVM with RBF Kernel (this may take 1 to 2 minutes) ...  

Training ......................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
.......................................... Done!  

Program paused. Press enter to continue.  

![image-20211030091055963](./pic/image-20211030091055963.png)

Loading and Visualizing Data ...  
Program paused. Press enter to continue.   

![image-20211030091127006](./pic/image-20211030091127006.png)

Training .......................... Done!  


Training .......................................... Done!  


Training ................................................ Done!  


Training ...................................................... Done!  


Training ................................................... Done!  


Training ................................................... Done!  


Training ........................................... Done!  


Training .......................................... Done!  


Training ....................................... Done!  


Training ................................................................ Done!  


Training ................................................... Done!  


Training ..................................................... Done!  


Training ......................... Done!  


Training ........................................... Done!  


Training ........................................................ Done!  


Training ......................................... Done!  


Training .................................... Done!  


Training ........................................................... Done!    

Training ......................................................................  
.................................................... Done!  

Training ......................................................................  
............ Done!  


Training .................................... Done!


Training .............................................. Done!  


Training ................................................. Done!  


Training ..................................................... Done!  


Training .............................................. Done!  

Training ......................................................................  
........ Done!

Training ......................................................................  
...............................................................................  
..................................... Done!  

Training ......................................................................  
...................... Done!  

Training ......................................................................  
................................ Done!  


Training ............................... Done!  


Training ............................................ Done!  


Training ........................................................... Done!  


Training ............................................ Done!  

Training ......................................................................  
...................... Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
............. Done!  

Training ......................................................................  
............................................................................ Done!  

Training ......................................................................  
... Done!  

Training ......................................................................  
.................... Done!  


Training ........................................................... Done!  


Training ..................................................... Done!  


Training .................................................. Done!  

Training ......................................................................  
. Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
........................................................................... Done!  

Training ......................................................................  
......................................................... Done!  


Training ..................................................................... Done!  


Training .................................................................. Done!  


Training .................................... Done!  


Training ................................ Done!  


Training ............................... Done!  


Training ............................................................... Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
................................................ Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
..................................................... Done!  

Training ......................................................................  
...............................................................................  
.............................. Done!      


Training ..................................................................... Done!    


Training ..................................................... Done!    


Training .......................................... Done!    


Training ..................................... Done!    


Training ..................................................... Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
............................................................... Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
...............................................................................  
............................................................................. Done!  

Training ......................................................................  
...............................................................................  
.............. Done!  

Training ......................................................................  
..................................... Done!  


Training ................................................................... Done!  


Training ...................................... Done!  

Training ......................................................................  
...............................................................................  
...............................................................................  
........................................................... Done!  

Program paused. Press enter to continue.  

![image-20211030091348875](./pic/image-20211030091348875.png)

## ex6_spam

Preprocessing sample email (emailSample1.txt)  

\=\=\=\= Processed Email \=\=\=\=    

anyon know how much it cost to host a web portal well it depend on how mani  
visitor you re expect thi can be anywher from less than number buck a month  
to a coupl of dollarnumb you should checkout httpaddr or perhap amazon ecnumb  
if your run someth big to unsubscrib yourself from thi mail list send an  
email to emailaddr  

\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\===  
Word Indices:  
 86 916 794 1077 883 370 1699 790 1822 1831 883 431 1171 794 1002 1893 1364 592 1676 238 162 89     688 945 1663 1120 1062 1699 375 1162 479 1893 1510 79  
9 1182 1237 810 1895 1440 1547 181 1699 1758 1896 688 1676 992 961 1477 71 530 1699 531  

Program paused. Press enter to continue.  

Extracting features from sample email (emailSample1.txt)  

\=\=\== Processed Email \=\=\==  

anyon know how much it cost to host a web portal well it depend on how mani  
visitor you re expect thi can be anywher from less than number buck a month  
to a coupl of dollarnumb you should checkout httpaddr or perhap amazon ecnumb  
if your run someth big to unsubscrib yourself from thi mail list send an  
email to emailaddr  

\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\==  
Length of feature vector: 1899  
Number of non-zero entries: 45  
Program paused. Press enter to continue.  

Training Linear SVM (Spam Classification)  
(this may take 1 to 2 minutes) ...  

Training ......................................................................  
...............................................................................  
.......................................................................... Done!  

Training Accuracy: 99.825000  

Evaluating the trained Linear SVM on a test set ...  
Test Accuracy: 98.700000  

Top predictors of spam:  
 our             (0.502489)  
 click           (0.469623)  
 remov           (0.420683)  
 guarante        (0.382854)  
 visit           (0.374153)  
 basenumb        (0.344395)  
 dollar          (0.323724)  
 will            (0.266732)  
 price           (0.264403)  
 nbsp            (0.259831)  
 most            (0.257038)  
 pleas           (0.256332)  
 lo              (0.254929)  
 ga              (0.245525)  
 da              (0.238294)    



Program paused. Press enter to continue.  

\=\=== Processed Email ====  

do you want to make dollarnumb or more per week if you ar a motiv and qualifi  
individu i will person demonstr to you a system that will make you dollarnumb  
number per week or more thi is not mlm call our number hour pre record number  
to get the detail number number number i need peopl who want to make seriou  
monei make the call and get the fact invest number minut in yourself now  
number number number look forward to your call and i will introduc you to  
peopl like yourself who ar current make dollarnumb number plu per week number  
number number numberljgvnumb numberleannumberlrmsnumb  
numberwxhonumberqiytnumb numberrjuvnumberhqcfnumb numbereidbnumberdmtvlnumb  

\=\==\==\==\==\==\==\==\==\==\==\====  

Processed spamSample1.txt  

Spam Classification: 1  
(1 indicates spam, 0 indicates not spam)  

## submit result

==                                   Part Name |     Score | Feedback  
==                                   --------- |     ----- | --------  
==                             Gaussian Kernel |  25 /  25 | Nice work!  
==         Parameters (C, sigma) for Dataset 3 |  25 /  25 | Nice work!  
==                         Email Preprocessing |  25 /  25 | Nice work!  
==                    Email Feature Extraction |  25 /  25 | Nice work!  
==                                   --------------------------------  
==                                             | 100 / 100 |  

## Optional (ungraded) exercise

### Try your own emails

In this part, we only need modify filename to try spam classifer on different sample.

```octave
% ex6_spam.m
%% =================== Part 6: Try Your Own Emails =====================
%  Now that you've trained the spam classifier, you can use it on your own
%  emails! In the starter code, we have included spamSample1.txt,
%  spamSample2.txt, emailSample1.txt and emailSample2.txt as examples. 
%  The following code reads in one of these emails and then uses your 
%  learned SVM classifier to determine whether the email is Spam or 
%  Not Spam

% Set the file to be read in (change this to spamSample2.txt,
% emailSample1.txt or emailSample2.txt to see different predictions on
% different emails types). Try your own emails as well!
filename = 'spamSample1.txt';

% Read and predict
file_contents = readFile(filename);
word_indices  = processEmail(file_contents);
x             = emailFeatures(word_indices);
p = svmPredict(model, x);

fprintf('\nProcessed %s\n\nSpam Classification: %d\n', filename, p);
fprintf('(1 indicates spam, 0 indicates not spam)\n\n');
```

My spam email is showed below, which comes from smartphones2020-space@quoramail.com.

```
Smart Phones News · 467k followers
The latest smart phones specifications, updates and comparisons.

Faryad Hussain, Blogger (2018-present)
Posted Sep 27
Xiaomi CIVI Launched6.55" FHD+ 120Hz Curved OLEDDolby Vision... Read More »

9 upvotes

Faryad Hussain, Blogger (2018-present)
Posted Sep 20
iQOO Z5 specifications.Launching on September 23 in China & On September 27 in India🇮🇳- 6.5" FHD+ LCD, 120hz refresh rate HDR 10+ & 10bit color... Read More »

Why is the iPhone 13 Pro and the iPhone13 Pro Max use the outdated 120Hz display instead of using a 240Hz display like the Aquos R6 phone?
Kyle Krebs, B.S. Electrical Engineering & Mathematics, The University of Utah (2019)
Written Sep 25
For the same reason most everyone else doesn’t use it, and likely won’t use it anytime soon. For the same reason TV manufacturers actually stopped producing 240Hz refresh r...

Read More »
```

The classification results are shown in the table below.

|  Sample  | Actual | Result |
|  ----  | ----  |  ----  |
| emailSample1.txt | non-spam | non-spam |
| emailSample2.txt | non-spam | non-spam |
| spamSample1.txt | spam | spam |
| spamSample2.txt | spam | spam |
| myspam.txt | spam | non-spam |

Input:     

\=\=\== Processed Email ====    

anyon know how much it cost to host a web portal well it depend on how mani    
visitor you re expect thi can be anywher from less than number buck a month    
to a coupl of dollarnumb you should checkout httpaddr or perhap amazon ecnumb    
if your run someth big to unsubscrib yourself from thi mail list send an    
email to emailaddr    

\==\==\=\=\=\=\=\=\=\=\=\==\=\=\=\=\=\=====    

Processed emailSample1.txt    

Spam Classification: 0    
(1 indicates spam, 0 indicates not spam)    


\=\=\== Processed Email ====    

folk my first time post have a bit of unix experi but am new to linux just    
got a new pc at home dell box with window xp ad a second hard disk for linux    
partit the disk and have instal suse number number from cd which went fine    
except it didn t pick up my monitor i have a dell brand enumberfpp number lcd    
flat panel monitor and a nvidia geforcenumb tinumb video card both of which    
ar probabl too new to featur in suse s default set i download a driver from    
the nvidia websit and instal it us rpm then i ran saxnumb as wa recommend in    
some post i found on the net but it still doesn t featur my video card in the    
avail list what next anoth problem i have a dell brand keyboard and if i hit    
cap lock twice the whole machin crash in linux not window even the on off    
switch is inact leav me to reach for the power cabl instead if anyon can help    
me in ani wai with these prob i d be realli grate i ve search the net but    
have run out of idea or should i be go for a differ version of linux such as    
redhat opinion welcom thank a lot peter irish linux user group emailaddr    
httpaddr for un subscript inform list maintain emailaddr    

\==\==\=\=\=\=\=\=\=\=\=\==\=\=\=\=\=\=====    

Processed emailSample2.txt    

Spam Classification: 0    
(1 indicates spam, 0 indicates not spam)    


\=\=\== Processed Email ====    

do you want to make dollarnumb or more per week if you ar a motiv and qualifi    
individu i will person demonstr to you a system that will make you dollarnumb    
number per week or more thi is not mlm call our number hour pre record numbe    r
to get the detail number number number i need peopl who want to make seriou    
monei make the call and get the fact invest number minut in yourself now    
number number number look forward to your call and i will introduc you to    
peopl like yourself who ar current make dollarnumb number plu per week number    
number number numberljgvnumb numberleannumberlrmsnumb    
numberwxhonumberqiytnumb numberrjuvnumberhqcfnumb numbereidbnumberdmtvlnumb    

\==\==\=\=\=\=\=\=\=\=\=\==\=\=\=\=\=\=====    

Processed spamSample1.txt    

Spam Classification: 1    
(1 indicates spam, 0 indicates not spam)    


\=\=\== Processed Email ====    

best bui viagra gener onlin viagra numbermg x number pill dollarnumb free    
pill reorder discount top sell number qualiti satisfact guarante we accept    
visa master e check payment number satisfi custom httpaddr    

\==\==\=\=\=\=\=\=\=\=\=\==\=\=\=\=\=\=====    

Processed spamSample2.txt    

Spam Classification: 1    
(1 indicates spam, 0 indicates not spam)    


\=\=\== Processed Email ====    

smart phone new numberk follow the latest smart phone specif updat and    
comparison faryad hussain blogger number present post sep number xiaomi civi    
launchednumb number fhd numberhz curv oleddolbi vision read more number upvot    
faryad hussain blogger number present post sep number iqoo znumber specif    
launch on septemb number in china on septemb number in india number number    
fhd lcd numberhz refresh rate hdr number numberbit color read more why is the    
iphon number pro and the iphonenumb pro max us the outdat numberhz displai    
instead of us a numberhz displai like the aquo rnumber phone kyle kreb b s    
electr engin mathemat the univers of utah number written sep number for the    
same reason most everyon els doesn t us it and like won t us it anytim soon    
for the same reason tv manufactur actual stop produc numberhz refresh r read    
more    

\==\==\=\=\=\=\=\=\=\=\=\==\=\=\=\=\=\=====    

Processed myspam.txt    

Spam Classification: 0    
(1 indicates spam, 0 indicates not spam)    
