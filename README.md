 # ThinkStats #
 __Conditional Distribution:__  As the name itself indicates that the distribution of data based on a condition.
For example, you are given a large set of data and you are interested in a particular item in that data, and its characteristics and how it varies in accordance with the data can be known using Conditional Distribution.
 
 
 For example, you could say we’re only interested in how computers are used for English classes or the Social Sciences. The highlighted areas in the chart below are the conditional distributions for Math (blue) and Social Sciences (yellow).
 
 <p align="center"> 
  <img src="https://cdn.discordapp.com/attachments/405443897578356738/405444239883894785/CD1.PNG">
</p>

Above example is a small demonstration of how we can know a particular relation. In reality, we are given large chunks of data and are asked to extract the data.

__Pareto Distribution:__ The Pareto distribution is named after the economist Vilfredo Pareto, who
used it to describe the distribution of wealth.
Since then, it has been used to describe phenomena in the natural and social sciences including sizes of cities and towns, sand particles and meteorites, forest fires and earthquakes.

It is defined by a shape parameter α ( slope parameter or Pareto Index) and a location parameter, X

In the real world, it has two main applications like:

1.To model the distribution of incomes.
1.To model the distribution of city populations.

The Pareto distribution is expressed as:

F(x) = 1 – (k/x)<sup>α</sup> <br>
where<br>
x is the random variable<br>
k is the lower bound of the data<br>
α is the shape parameter.<br>

* __Survival Function:__ It is also referred as a tail function or reliability function Sometimes. 	This is just the probability of values greater than X. <br>
For example, whenever you are looking at the population in the India and want to know what proportion of population is greater than 10 million.

<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405447102832050176/PD.PNG">
</p>

__Cumulative distribution function:__ <br>
Cumulative distribution function of a Pareto random variable with parameters α and x<sub>m</sub>  is <br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405447113422405633/13133.PNG">
</p><br>

where x<sub>m</sub> ( or k) is the minimum possible value.

## Normal distribution: <br>
Normal (or __Gaussian__) distribution is a continuous probability distribution.
It is sometimes called as __Bell Curve__. <br>

__For Example:__  <br>
The Bell curve is seen in tests like IIT, AIEEE,CAT etc. The bulk of students will score the average (C), while smaller numbers of students will score a B or D. An even smaller percentage of students score an F or an A. This creates a distribution that resembles a bell . The bell curve is symmetrical. Half of the data will fall to the left of the mean; half will fall to the right.<br>

<p>
 <img style=" height="30%" width="30%"  " src ="https://cdn.discordapp.com/attachments/405443897578356738/405447091150782495/nd.PNG"> 
<img style=" height="20%" width="30%" " src ="https://cdn.discordapp.com/attachments/405443897578356738/405447106430763009/1222.PNG">
 </p>
 
 ### Properties of a normal distribution: <br>
 * The mean, mode and median are all equal.<br>
 * The curve is symmetric at the center (i.e. around the mean, μ).<br>
 * Exactly half of the values are to the left of center and exactly half the values are to the right.<br>
 * The total area under the curve is 1. <br>
 <br>
 The empirical rule tells you what percentage of your data falls within a certain number of standard deviations from the mean: <br>
 
* 68% of the data falls within one standard deviation of the mean. <br>
* 95% of the data falls within two standard deviations of the mean.<br>
* 99.7% of the data falls within three standard deviations of the mean.<br>

<br>
<p align ="center">
<img  style= " height="60%" width="60%" " src="https://cdn.discordapp.com/attachments/405443897578356738/405447112612904981/12323.PNG">
</p><br>
<br>
The normal distribution has many properties that make it amenable for analysis, but the CDF is not one of them. Unlike the other distributions we have looked at, there is no closed-form expression for the normal CDF; the most common alternative is to write it in terms of the **error function** ,which is a special function written **erf(x)** .  
<br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405447123052789760/723782.PNG">
</p><br>

## Bayes Theorem: <br>
Bayes’ theorem is to determine conditional probability. A __conditional probability__ is an expression of how probable one event is, given that some other event occurred. <br>
<br>
* ### Conditional Probability: <br>
   Consider two events A and B <br>
* Event A is the probability of the event we are trying to calculate.<br>
* Event B is the condition that we know or the event that has happened.<br>
We can write the conditional probability as P(A/B), the probability of the occurrence of event A given that B has already happened.<br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405447108875911170/2312.PNG">
</p>

**Let’s take a example:**

* Suppose you have a jar containing 6 marbles – 3 black and 3 white. What is the probability of getting a black given the first one was black too. <br>
P (A) = getting a black marble in the first turn <br>
P (B) = getting a black marble in the second turn <br>
P (A) = 3/6  <br>
P (B) = 2/5  <br>
P (A and B) = (1/2)*(2/5) = 1/5  <br>
<p>
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405728932478844940/unknown.png">
</p><br>
For better understanding solve some problems on conditional probability.<br>
<br>

**Baye’s Theorem Statement:**

<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405447116790562817/14234.PNG">
</p>

The **Sample Space(S)** of an experiment or random trial is the set of all possible outcomes or results of that experiment. <br>

The Bayes theorem describes the probability of an event based on the prior knowledge of the conditions that might be related to the event. If we know the conditional probability P(A/B), we can use the bayes rule to find out the reverse probabilities P(B/A). <br>
Baye’s theorem has wide range of applicabilities in various domains like detecting flaws , testing cancer , business analysis etc.<br>

**Let’s consider a simple example:**

In a particular pain clinic, 10% of patients are prescribed narcotic pain killers. Overall, five percent of the clinic’s patients are addicted to narcotics (including pain killers and illegal substances). Out of all the people prescribed pain pills, 8% are addicts. If a patient is an addict, what is the probability that they will be prescribed pain pills? <br>
Sol: <br>
P(A) =  The event that happens first (A) is being prescribed pain pills. That’s given as 10%. <br>
i.e  P(A)= (10/100)=0.1 <br>

Event B is being an addict. That’s given as 5% <br>
i.e  P(B)= (5/100)=0.05 <br>

P(B/A)= It’s the probability of being an addict , given that the people are prescribed pain kills. <br>
Threrefore, P(B/A)= (8/100) = 0.08 <br>

__Required to find:__ If a patient is an addict, what is the probability that they will be prescribed pain pills? i.e __P(A/B)__

According to Baye’s theorem,<br> 
 
P(A|B) = [P(B|A) * P(A) ]/ P(B) = (0.08 * 0.1)/0.05 = 0.16 <br>
<br>
## Convolution: <br>

There are various definitions for convolution in probability theory and statistics. I will try to quote some of them here in a precise manner.<br>

The convolution of probability distributions corresponds to the addition of independent random variables and, by extension, to forming linear combinations of random variables.<br>

The probability distribution of the sum of two or more independent random variables is the convolution of their individual distributions.<br>

It can be generally understood as, <br>
Suppose we have two random variables, X and Y, with distributions CDF<sub>X</sub> and
CDF<sub>Y</sub>. What is the distribution of the sum  
Z = X + Y?  is convolution

__Proof:__ <br>
There are several methods in which we can demonstrate the proof, but this one is simple and versatile.<br>
Given any RandomVariables, X and Y, we can create a Sum object that represents Z. Then we can use a sample from Z to approximate CDF<sub>Z</sub>. <br>
Here CDF<sub>X</sub> and CDF<sub>Y</sub> are expressed as functions. <br>
<br>

**Step-1:** 

Assume that the particular value of X is x, then CDF<sub>Z</sub>(z) is : <br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405740327551369226/unknown.png">
</p><br>
Here LHS represents the probability that the sum is less than z, given that the first term is x. And, if the first term is x and the sum has to be less than z, then the second term has to be less than z − x. <br>

**Step-2:**

To get the probability that Y is less than z − x, we evaluate CDF<sub>Y</sub>  <br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405745191568277514/unknown.png">
</p>

**Step-3:**

But we don’t actually know the value of x, we have to consider all values it could have and integrate over them:  <br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405745824484687876/unknown.png">
</p><br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405745879992238080/unknown.png">
</p><br>
<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405745948321644555/unknown.png">
</p><br>
(Since the LHS represents the definition of CDFZ )

**Step-4:**

To get PDF<sub>Z</sub> , take the derivative of both sides with respect to z. The result is : <br>

<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405747982051573761/unknown.png">
</p><br>

You have might have seen this integral in your higher mathematics subjects. It is the
convolution of PDFY and PDFX, denoted with the operator ∗  <br>
<p align ="center">
 PDF<sub>Z</sub>  = PDF<sub>Y</sub> ∗ PDF<sub>X</sub>   
</p><br>
<br>

## Chi Square test:  

A chi-squared test, also written as <p><img src="https://cdn.discordapp.com/attachments/405443897578356738/405447119302950923/87387.PNG"></p> test, is any statistical hypothesis test where the sampling distribution of the test statistic is a chi-squared distribution when the **null 		hypothesis** is true.

The chi-squared distribution with k degrees of freedom is the distribution of a sum of the squares of k independent standard normal random variables.<br>
The chi-squared distribution is used in the common chi-squared tests for goodness of fit of an observed distribution to a theoretical one, the independence of two criteria of classification of qualitative data, and in confidence interval estimation for a population standard deviation of a normal distribution from a sample standard deviation.<br>
<br>
The statement being tested in a test of statistical significance is called the null hypothesis. The test 
of significance is designed to assess the strength of the evidence against the null hypothesis. Usually, 
the null hypothesis is a statement of 'no effect' or 'no difference'. <br>
* Procedure: <br>
1)We define a set of categories, called cells. <br>
2)Under the null hypothesis, we assume that the distributions are the same for 	the 	two 	groups, so we can compute the pooled probabilities. <br>
3)For each cell we compute the deviation; that is, the difference between the observed
value, O<sub>i</sub> , and the expected value, E<sub>i</sub>. <br>
4)We compute some measure of the total deviation; this quantity is called the test
statistic. The most common choice is the chi-square statistic. <br>

<p align ="center">
<img src="https://cdn.discordapp.com/attachments/405443897578356738/405751472391979008/unknown.png">
</p><br>

5). We can use a Monte Carlo simulation to compute the p-value, which is the probability of 	seeing a chi-square statistic as high as the observed value under the null hypothesis.<br>
<br>
A low value for chi-square means there is a high correlation between your two sets of data. In 	theory, if your observed and expected values were equal (i.e. no difference ) ,then chi-square 	would be zero — an event that is unlikely to happen in real life. <br>

**Note:**

 The Chi-square statistic can only be used on numbers. They can’t be used for percentages, 	proportions, means or similar statistical value. For example, if you have 10 percent of 200 people, 	you would need to convert that to a number (20) before you can run a test statistic. <br>
 
 * The number of degrees of freedom= (r – 1) (c – 1) in which r is the number of rows and c the 	number of columns in which the data are tabulated.<br>
 
 **Applications of chi-squared distribution:**

1)Chi-square test can be applied to complex contingency table with several classes. <br>
2) Chi-square test has a very useful property i.e., ‘the additive property’. If a number of sample studies are conducted in the same field, the results can be pooled together. This means that χ2-values can be added. <br>
3)Although test is conducted in terms of frequencies it can be best viewed conceptually as a test about proportions. <br>











