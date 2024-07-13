# Basic-Statistics-L2
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
(i)	What is inter-quartile range of this dataset? (please approximate the numbers) In one line, explain what this value implies.
UQ=12.5, LQ=5
IQR = 12-5 = 7
(ii)	What can we say about the skewness of this dataset?
Acc to boxplot mean >median. It is positively skewed data since the major tail lies on the right side.
(iii)	If it was found that the data point with the value 25 is actually 2.5, how would the new box-plot be affected?
In this case there are no outliers. Under this condition the median will shift from current position to more right side to 7.5. The data will be normally distributed.

3. ![image](https://github.com/user-attachments/assets/6e05196d-7a11-4921-80da-074e4a6d5da0)

Answer the following three questions based on the histogram above.
(i)	Where would the mode of this dataset lie?
Mode will appear between 4-8
(ii)	Comment on the skewness of the dataset.
Here mean > median. Median is towards the left, positively skewed data.
(iii)	Suppose that the above histogram and the box-plot in question 2 are plotted for the same dataset. Explain how these graphs complement each other in providing information about any dataset. 
They both are right-skewed, and both have outliers the median can be easily visualized in box plot where as in histogram mode is more visible.

3.	AT&T was running commercials in 1990 aimed at luring back customers who had switched to one of the other long-distance phone service providers. One such commercial shows a businessman trying to reach Phoenix and mistakenly getting Fiji, where a half-naked native on a beach responds incomprehensibly in Polynesian. When asked about this advertisement, AT&T admitted that the portrayed incident did not actually take place but added that this was an enactment of something that “could happen.” Suppose that one in 200 long-distance telephone calls is misdirected. What is the probability that at least one in five attempted telephone calls reaches the wrong number? (Assume independence of attempts.)

Solution:
Probability of call misdirect = 1/200 = 0.005
Probability of no call misdirect = 1-1/200 = 0.995
The probability for at least one in five attempted telephone calls reaches the wrong number, Number of calls = 5
n = 5, p=0.005, q=0.995
P (1) = 1 – Probability that all five calls are not misdirected
         = 1 – (1 – 0.005)^5
         = 1 – 0.975
         = 0.0245

Therefore, the probability that at least one in five attempted telephone calls reaches the wrong number is 0.0245.

4.	Returns on a certain business venture, to the nearest $1,000, are known to follow the following probability distribution
   
| x |	P(x) |
| ----- | ----- |
| -2,000 | 0.1 |
| -1,000 | 0.1 |
| 0 | 0.2 |
| 1000 |	0.2 |
| 2000 |	0.3 |
| 3000 |	0.1 |

* What is the most likely monetary outcome of the business venture?
<br/>
Most likely monetary outcome is 2000$. This is maximum among all the outcomes.


* Is the venture likely to be successful? Explain
<br/>
Yes, it will be successful.
<br/>
P(x>0)+ P(x>1000)+ P(x>2000)+ P(x>3000) = 0.2+0.2+0.3+0.1= 0.8.
<br/>
This means that the venture has chances to be 80% successful.
<br/>
* What is the long-term average earning of business ventures of this kind? Explain
<br/>
The long-term average earning expected value= Sum(X*P(X))= 0.8*1000$=800$,
<br/>
Which means on an average the return will be 800$.
<br/>
* What is the good measure of the risk involved in a venture of this kind? Compute this measure.
<br/>
The good measure of the risk involved in a venture of this kind depends on the Variability in the distribution.
<br/>
Higher variance means more chances of risk.
<br/>
Var(X)= E(X^2)-(E(X)^2)= 2800000-(800*800)=2160000.







