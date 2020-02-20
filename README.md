# Drowsiness-Dectetion
<h3>Team Member</h3>
Chule Hou
<h3>Project Title</h3>
Drowsiness Detection
<h3>Project Overview</h3>
<p>There are many people who work for long-distance freight drivers. Their job is to drive trucks for long periods of time, 
so driving time is a factor in determining their wages. Many drivers want to get their goods to their destination faster, 
so they will sacrifice normal sleep time to drive. In this case, it is very easy to cause a driving accident caused by drowsiness. 
So, I hope that there is a program that can remind the driver to concentrate on driving while the driver is asleep or find a rest stop. 
Many cars now have a reminder of fatigue driving, but the principle of these reminders is based on the driver's driving time. 
If a driver drives the driver for more than three hours, he will remind the driver to rest, but such a procedure does not effectively 
remind the driver who is in a dozing state.But Tesla's autonomous driving is only in small cars, and trucks still need humans to 
control and drive. Therefore, how to make humans drive cars more efficiently and reduce traffic accidents as much as possible becomes 
a problem that we all need to think about.</p>
<h3>Project Methods</h3>
<p>I will use an external camera to get outside information for analysis. External information is passed into this algorithm, 
the algorithm makes analysis and judgment, and outputs the result.</p>
![image](https://https://github.com/ChuleHou/Drowsiness-Dectetion/blob/master/images/image1.png)
<p>There is a paper that wrote by Soukupová and Čech in 2016.  In them research, they set the four landmarks around the eyes. They use the eye aspect ratio EAR in Eq to make sure the eye-opening in. If the ration is constant, then rapidly drops to zero, then increases again, indicating a blink has taken place. If the ration does not increase again, thus implying that the person has closed their eyes. I will use this method to determine if the driver is dozing.This picture is come from the paper wrote by Tereza Soukupova and Jan ´ Cech. In the top-left picture, the open and closed eyes with landmarks Pi automatically detected. These landmarks will be used to calculate for the eye aspect ratio. I also need to set the threshold.
If the eye aspect ratio falls below this threshold, I will start counting the number of frames the person has closed their eyes for. 
If the number of frames the person has closed their eyes in exceeds the threshold that set to determine if the person want to sleep. 
And then the program will play some alarm to remind the driver be careful to drive.</p>
<p>In conclusion, after I finish this program, I will test it in the real life. 
I hope it can be helpful for drivers. I also hope that it will be possible to reduce the driver’s 
drowsiness because of insufficient rest, and finally cause a big traffic accident, which can be avoided.</p>
<h3>Camera Use</h3>
<h3>Result</h3>
