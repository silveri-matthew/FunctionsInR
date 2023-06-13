<h1>Statistics using R</h1>


<h2>Description</h2>
Statistic functions and modeling using R.
<br />


<h2>Methods Used</h2>

- <b>T test</b>
- <b>Confidence Interval</b> 
- <b>Population Mean</b> 
- <b>Sample Proportion</b> 
- <b>Two Sample T Test</b> 
- <b>Scatter Plot</b> 
- <b>Pearson's Correlation</b> 
- <b>Linear Regression</b> 
- <b>ANOVA</b> 
- <b>Tukey</b> 

<h2>Materials Used </h2>

- <b>RStudio</b>
- <b>MASS package</b>

<h2>Project walk-through:</h2>

<p align="center">
Number of observations in the set: <br/>
<img src="https://imgur.com/G8BcECZ.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Number of variables in the set:  <br/>
<img src="https://imgur.com/rfYWqEK.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Variable type of HeadWT:  <br/>
<img src="https://imgur.com/h8Csux6.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Five number summary for HeadWT:  <br/>
<img src="https://imgur.com/QzbAWNY.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Outliers in HeadWT: <br/>
<img src="https://imgur.com/vWwjKTt.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
95% confidence interval to estimate the population mean of weight of the cabbage head (HeadWt):  <br/>
<img src="https://imgur.com/YejFG10.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
The researcher wants to prove the population mean of weight of the cabbage head is heavier than 2.5 (kg). State the null and alternative hypothesis. Perform the hypothesis test and make your decision based on comparing p-value to 0.05:  <br/>
<img src="https://imgur.com/j7I7jmc.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
<p align="left">
Null: head is less than or equal to 2.5
Alt: The population mean weight of the cabbage is heavier than 2.5 kg
We fail to reject. The population mean of the cabbage head is not greater than 2.5
<br />
<br />
<p align="center">
type of Cult variable:  <br/>
<img src="https://imgur.com/jnjsNbK.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
<p align="left">
Categorical
<br />
<br />
<p align="center">
90% confidence interval to estimate the population proportion of c39 cabbage: <br/>
<img src="https://imgur.com/Qd4xBWq.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Subset of data set whose cultivar (Cult) of cabbage is c39:  <br/>
<img src="https://imgur.com/gBIeQPw.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<img src="https://imgur.com/a5xRSOo.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Subset of data set whose cultivar (Cult) of cabbage is c52: <br/>
<img src="https://imgur.com/sA2FTDi.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<img src="https://imgur.com/RWnUzlL.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Tapply() function to find standard deviation of weight of the c39 cabbage head and standard deviation of weight of the c52 cabbage head:  <br/>
<img src="https://imgur.com/Kafed4k.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
95% confidence interval for the difference between the mean of weight of the c39 cabbage head and the mean of weight of the c52 cabbage head:  <br/>
<img src="https://imgur.com/kz5IGOR.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<p align="left">
check for equal variance
<br />
<br />
<img src="https://imgur.com/YedIjjZ.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
We are 95% confident that the difference is between 0.197 and 1.056
<br />
<br />
<p align="center">
The researcher wants to show mean of weight of the c39 cabbage head is different from the mean of weight of the c52 cabbage head. State the null and alternative hypotheses. Perform the hypothesis test and make your decision based on comparing p-value to 0.05:  <br/>
<img src="https://imgur.com/sZO6uBS.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<p align="left">
Check for equal variance. Less than 2 and more than 0.5.
If not equal then var.equal = F
Null: mean weight of c39 – c52 is equal to zero
Alt: mean weight of c39 – c52 is not equal to zero
<br />
<br />
<img src="https://imgur.com/aXYq4mC.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
Reject the null. The mean weight of the c39 head is not equal to the mean weight of the c59 cabbage head.
<br />
<br />
<p align="center">
Type of VitC variable:  <br/>
<img src="https://imgur.com/Deb2pbQ.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Scatter plot between HeadWt (x-axis) and VitC (y-axis):  <br/>
<img src="https://imgur.com/sSZtgpf.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Pearson's correlation between HeadWt and VitC:  <br/>
<img src="https://imgur.com/OGCNozq.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Simple linear regression analysis with VitC as response variable and HeadWt as explanatory variable:  <br/>
<img src="https://imgur.com/sxqp7KP.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Update the scatter plot of problem 18 with the fitted linear regression line:  <br/>
<img src="https://imgur.com/SKI5IE0.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
What is the type of Date variable:  <br/>
<img src="https://imgur.com/K9gLSd6.png" height="80%" width="80%" alt="Project walk-through"/>
<p align="left">
Categorical
<br />
<br />
<p align="center">
We want to check whether the ascorbic acids content (VitC) of cabbages for three different planting dates are different. State the null and alternative hypotheses and then perform one-way ANOVA. If necessary, perform Tukey’s Honestly Differences Test:  <br/>
<img src="https://imgur.com/WnLwwPk.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<img src="https://imgur.com/pXUzSyN.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<p align="left">
Null: all equal
Alt: at least one is not equal
<br />
<img src="https://imgur.com/nBgHeGC.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<img src="https://imgur.com/2YwoX2l.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<img src="https://imgur.com/lBpFmR8.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
Reject the null as at least one is less than the significance level and both lwr and upr are positive or negative.
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
