# Basic-Statistics-L2 - Set 1
_**<p align = "center">Topics: Descriptive Statistics and Probability</p>**_

1. Look at the data given below. Plot the data, find the outliers and find out

   | Name of company | Measure X |
   | --------------- | --------- |
   | Allied Signal | 24.23% |
   | Bankers Trust | 25.53% |
   | General Mills | 25.41% |
   | ITT Industries | 24.14% |
   | J.P.Morgan &amp; Co. | 29.62% |
   | Lehman Brothers | 28.25% |
   | Marriott | 25.81% |
   | MCI | 24.39% |
   | Merrill Lynch | 40.26% |
   | Microsoft | 32.95% |
   | Morgan Stanley | 91.36% |
   | Sun Microsystems | 25.99% |
   | Travelers | 39.42% |
   | US Airways | 26.71% |
   | Warner-Lambert | 35.00% |

A. 91 data point is outlier.

![image](https://github.com/user-attachments/assets/ee20f111-9246-414d-be7f-467181bf7de8)

![image](https://github.com/user-attachments/assets/84890a58-98c6-4ecb-8d42-32a6a2a02acc)

2. ![image](https://github.com/user-attachments/assets/21044d4f-058e-45e2-a493-44eb88278a49)

Answer the following three questions based on the box-plot above.
<br/>
(i)	What is inter-quartile range of this dataset? (please approximate the numbers) In one line, explain what this value implies.
<br/>
UQ=12.5, LQ=5
<br/>
IQR = 12-5 = 7
<br/>
(ii)	What can we say about the skewness of this dataset?
<br/>
Acc to boxplot mean >median. It is positively skewed data since the major tail lies on the right side.
<br/>
(iii)	If it was found that the data point with the value 25 is actually 2.5, how would the new box-plot be affected?
<br/>
In this case there are no outliers. Under this condition the median will shift from current position to more right side to 7.5. The data will be normally distributed.
<br/>

3. ![image](https://github.com/user-attachments/assets/6e05196d-7a11-4921-80da-074e4a6d5da0)

Answer the following three questions based on the histogram above.
<br/>
(i)	Where would the mode of this dataset lie?
<br/>
Mode will appear between 4-8
<br/>
(ii)	Comment on the skewness of the dataset.
<br/>
Here mean > median. Median is towards the left, positively skewed data.
<br/>
(iii)	Suppose that the above histogram and the box-plot in question 2 are plotted for the same dataset. Explain how these graphs complement each other in providing information about any dataset. 
<br/>
They both are right-skewed, and both have outliers the median can be easily visualized in box plot where as in histogram mode is more visible.
<br/>

3.	AT&T was running commercials in 1990 aimed at luring back customers who had switched to one of the other long-distance phone service providers. One such commercial shows a businessman trying to reach Phoenix and mistakenly getting Fiji, where a half-naked native on a beach responds incomprehensibly in Polynesian. When asked about this advertisement, AT&T admitted that the portrayed incident did not actually take place but added that this was an enactment of something that “could happen.” Suppose that one in 200 long-distance telephone calls is misdirected. What is the probability that at least one in five attempted telephone calls reaches the wrong number? (Assume independence of attempts.)

Solution:
<br/>
Probability of call misdirect = 1/200 = 0.005
<br/>
Probability of no call misdirect = 1-1/200 = 0.995
<br/>
The probability for at least one in five attempted telephone calls reaches the wrong number, Number of calls = 5
<br/>
n = 5, p=0.005, q=0.995
<br/>
P (1) = 1 – Probability that all five calls are not misdirected
<br/>
         = 1 – (1 – 0.005)^5
         <br/>
         = 1 – 0.975
         <br/>
         = 0.0245
<br/>
Therefore, the probability that at least one in five attempted telephone calls reaches the wrong number is 0.0245.
<br/>

4.	Returns on a certain business venture, to the nearest $1,000, are known to follow the following probability distribution
   
| x |	P(x) |
| ----- | ----- |
| -2,000 | 0.1 |
| -1,000 | 0.1 |
| 0 | 0.2 |
| 1000 |	0.2 |
| 2000 |	0.3 |
| 3000 |	0.1 |

i) What is the most likely monetary outcome of the business venture?
<br/>
Sol) Most likely monetary outcome is 2000$. This is maximum among all the outcomes.

ii) Is the venture likely to be successful? Explain
<br/>
Sol) Yes, it will be successful.
<br/>
P(x>0)+ P(x>1000)+ P(x>2000)+ P(x>3000) = 0.2+0.2+0.3+0.1= 0.8.
<br/>
This means that the venture has chances to be 80% successful.
<br/>

iii) What is the long-term average earning of business ventures of this kind? Explain
<br/>
Sol) The long-term average earning expected value= Sum(X*P(X))= 0.8*1000$=800$,
<br/>
Which means on an average the return will be 800$.
<br/>

iv) What is the good measure of the risk involved in a venture of this kind? Compute this measure.
<br/>
Sol) The good measure of the risk involved in a venture of this kind depends on the Variability in the distribution.
<br/>
Higher variance means more chances of risk.
<br/>
Var(X)= E(X^2)-(E(X)^2)= 2800000-(800*800)=2160000.
<br/>
<br/>
# Basic-Statistics-L2 - Set 2

_**<p align = "center">Topics: Normal distribution, Functions of Random Variables</p>**_

1.	The time required for servicing transmissions is normally distributed with μ = 45 minutes and σ = 8 minutes. The service manager plans to have work begin on the transmission of a customer’s car 10 minutes after the car is dropped off and the customer is told that the car will be ready within 1 hour from drop-off. What is the probability that the service manager cannot meet his commitment? 

A.	0.3875   
B.	0.2676   
C.	0.5   
D.	0.6987 

Solution: 0.2676

![image](https://github.com/user-attachments/assets/ec3f0a19-2b62-440c-aed5-5c100bc2ace6)

2.	The current age (in years) of 400 clerical employees at an insurance claims processing center is normally distributed with mean μ = 38 and Standard deviation σ =6. For each statement below, please specify True/False. If false, briefly explain why.
A.	More employees at the processing center are older than 44 than between 38 and 44.
B.	A training program for employees under the age of 30 at the center would be expected to attract about 36 employees.

Solution:

![image](https://github.com/user-attachments/assets/c5d1f3b0-6945-4e85-b40e-04cdce6c014e)

3.	If X1 ~ N(μ, σ2) and X2 ~ N(μ, σ2) are iid normal random variables, then what is the difference between 2 X1 and X1 + X2? Discuss both their distributions and parameters.

Solution:  The normal distribution is interconnected with Central Limit Theorem and this states that large sum of independent identically distribution random variables fall under normal distribution then (X1+X2) and (2X1) have normal distribution as per this theory only if X1 and X2 are iid and n is large.

(X1+X2) and 2X1 differ in magnitude they hold of two different sample subsets (X1 & X2) from the same source (population). The distribution remains the same for every sample subset of similar source, it tends to fall under Normal distribution and slight deviations in parameters.

4.	Let X ~ N(100, 202). Find two values, a and b, symmetric about the mean, such that the probability of the random variable taking a value between them is 0.99. 

A.	90.5, 105.9 
B.	80.2, 119.8 
C.	22, 78 
D.	48.5, 151.5 
E.	90.1, 109.9

Solution: 48.5, 151.5

![image](https://github.com/user-attachments/assets/a0351642-f478-4726-aaf3-a807eb9a7c31)

5.	Consider a company that has two different divisions. The annual profits from the two divisions are independent and have distributions Profit1 ~ N(5, 32) and Profit2 ~
N(7, 42) respectively. Both the profits are in $ Million.
<br/>
Answer the following questions about the total profit of the company in Rupees. Assume that $1 = Rs. 45
<br/>
A.	Specify a Rupee range (centered on the mean) such that it contains 95% probability for the annual profit of the company.
<br/>
Rupee ranges in between [9.9 to 98.1] Crore Rupees, 95\\% of the time for the Annual Profit of the Company.
<br/>
B.	Specify the 5th percentile of profit (in Rupees) for the company.
<br/>
The 5TH Percentile of profit for the company is 17 Crore Rupees
<br/>
C.	Which of the two divisions has a larger probability of making a loss in a given year?
<br/>
The Division #2 (Profit2 ~ N(7, 42) ) has a larger probability of making a loss in a given year
<br/>






