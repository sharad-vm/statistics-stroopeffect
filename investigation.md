
**1. What is our independent variable? What is our dependent variable?**

   Our independent variable is the congruent or incongruent word that 
   is printed and our dependent variable is the amount of time taken by the participants to name the ink colors.

**2. What is an appropriate set of hypotheses for this task? What kind of statistical test do you expect to perform? 
   Justify your choices.**
   
   As Null hypothesis states that there is no relationship or nothing changes between two measured phenomena, the appropriate null 
   hypothesis (H<sub>0</sub>) in this task is that there is no difference in time taken to identify the coor of the words in either 
   congruent or incongruent conditions. 
   
   And the appropriate alternative hypothesis (H<sub>A</sub>) is that the incongruent word condition would take longer than the congruent 
   word condition. 
   
   H<sub>0</sub>: μ<sub>i</sub> = μ<sub>c</sub> (μ<sub>i</sub> - population mean of incongruent values, μ<sub>c</sub> - population mean 
   of congruent values) 
   
   H<sub>A</sub>: μ<sub>i</sub> > μ<sub>c</sub> (μ<sub>i</sub> - population mean of incongruent values, μ<sub>c</sub> - population mean 
   of congruent values)
   
   In other words, if the difference in means of incongruent and congruent word conditions is equal to 0, it means the time taken to say 
   the color out loud in both the conditions is the same and that the null hypothesis is true else, if the difference is greater than 0 
   then it means that the time taken in the incongruent condition is more than the tome taken in the congruent condition and that the 
   alternativee hypothesis is true.
   
   **Assumptions**
   
   As we don't know the population standard deviation and that we have a sample size of less than 30, the most appropriate statistical 
   score for hypothesis testing is a t-score. And as it looks like the same participants are taking both the tests at different times 
   with different conditions, we have dependent samples. We can compare the two means of dependent samples with a one-tailed t-test.
   
**3. Report some descriptive statistics regarding this dataset. 
   Include at least one measure of central tendency and at least one measure of variability.**

   | Statistics      | Congruent     | Incongruent  | Difference   |
   | --------------- |:-------------:| ------------:| ------------:|
   | Mean            | 14.05         | 22.01        | 7.96         |
   | Median          | 14.35         | 21.01        | 7.66         |
   | Pop. Variance   | 12.14         | 22.05        | 22.68        |
   | Pop. Std. Dev.  | 3.48          | 4.69         | 4.76         |
   | Sample Variance | 12.66         | 23.01        | 11.58        |
   | Sample Std. Dev.| 3.55          | 4.79         | 3.4          |
      
   
**4. Provide one or two visualizations that show the distribution of the sample data. 
   Write one or two sentences noting what you observe about the plot or plots.**
   
   ![alt text](https://github.com/sharad-vm/statistics-stroopeffect/blob/master/congruent-incongruent-histoogram.png  "Histogram of Congruent & Incongruent conditions")
   
   By plotting the congruent and incongruent word condition histograms as displayed above, it is clearly evident that the incongruent words have taken longer time to be identified than congruent. 
   
   ![alt text](https://github.com/sharad-vm/statistics-stroopeffect/blob/master/congruent-normal.png "Normal distribution of congruent condition")
   
   ![alt text](https://github.com/sharad-vm/statistics-stroopeffect/blob/master/incongruent-normal.png "Normal distribution of incongruent condition")
   
   As shown above, both the word conditions are more or less normally distributed with a few outliers in incongruent word condition and the means of the conditions can also be verified in the figures above.
   
 **5. Now, perform the statistical test and report your results. What is your confidence level and your critical statistic value? 
   Do you reject the null hypothesis or fail to reject it? Come to a conclusion in terms of the experiment task. 
   Did the results match up with your expectations?**
   
   Based on the alternative hypothesis, the appropriate test that should be conducted is one tailed positive direction test.
   
   Words in the lists (or sample size), n = 24
   
   Degrees of freedom,                 df = 23
   
   t-critical for $\alpha$ = .05, t-critical = 1.714
   
   Std error of the mean, SEM = 4.86/$\sqrt{24}$ = 0.992
   
   Mean difference = 22.01 - 14.05 = 7.96
   
   t-statistic = Mean difference/SEM = 7.96/0.992 = 8.02
   
   The p-value in this case is greater than 0.05 and the results are statistically significant.
   
   Because the t-statistic is greater than the t-critical, it is safe to reject the null hypothesis. This means that it  does take longer to say the color out loud in the condition of incongruent words than congruent words and matches my expectations which is also the alternative hypothesis.
   
**6. Optional: What do you think is responsible for the effects observed? Can you think of an alternative or similar task that would 
   result in a similar effect? Some research about the problem will be helpful for thinking about these two questions!**
   
   I think the brain takes longer to connect the incongruent word with the color the word is in while in the case of congruent words, recognizing the color of the word or reading the word is good enough as they both would be the same. 
   
   An alternative to this task would be to use reversed words instead of regular words.
   
   Example - Congruent words - RED GREEN BLUE
             Incongruent words - DER NEERG EULB
   
**References**

+ [Udacity's Statistics Course](https://classroom.udacity.com/nanodegrees/nd002/parts/0021345402/modules/458220420175460/lessons/4621269407/concepts/2302290830923)

+ [Wikipedia - Stroop Effect](https://en.wikipedia.org/wiki/Stroop_effect)

+ [T-Score vs. Z-Score: What's the Difference?](http://www.statisticshowto.com/when-to-use-a-t-score-vs-z-score/)
