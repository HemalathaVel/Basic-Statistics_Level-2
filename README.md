# Statistics-Level-2

**1. Topics: Descriptive Statistics and Probability**

**Look at the data given below. Plot the data, find the outliers and find out  μ,σ,σ^2**

Name of company	Measure X
Allied Signal	24.23%
Bankers Trust	25.53%
General Mills	25.41%
ITT Industries	24.14%
J.P.Morgan & Co.	29.62%
Lehman Brothers	28.25%
Marriott	25.81%
MCI	24.39%
Merrill Lynch	40.26%
Microsoft	32.95%
Morgan Stanley	91.36%
Sun Microsystems	25.99%
Travelers	39.42%
US Airways	26.71%
Warner-Lambert	35.00%


Ans:  In the above data set Morgan Stanley at 91.36% is the outlier in the boxplot.

Mean (µ) = 33.271                        

![image](https://github.com/HemalathaVel/Statistics-Level-2/assets/154992818/d5e486f9-e36a-4b82-8228-58f8683b82f6)

Variance(σ2) = 287.146612

![image](https://github.com/HemalathaVel/Statistics-Level-2/assets/154992818/3ccb5d3f-0ba6-4a73-8fc1-f499507e7489)

Standard Deviation (σ) = 16.945401

![image](https://github.com/HemalathaVel/Statistics-Level-2/assets/154992818/95e792ea-c1db-44f2-9b91-2996fe53b288)


2.
![image](https://github.com/HemalathaVel/Statistics-Level-2/assets/154992818/55120281-3015-4baf-8c33-636d08f6bdf0)

**Answer the following three questions based on the box-plot above.
(i)	What is inter-quartile range of this dataset? (please approximate the numbers) In one line, explain what this value implies.
(ii)	What can we say about the skewness of this dataset?
(iii)	If it was found that the data point with the value 25 is actually 2.5, how would the new box-plot be affected?**


Ans:
i)	Approximately Q1 = 5
                 Q3 = 12
  Inter- quartile = Q3 -Q1
                  = 12 – 5
                  = 7
Second Quartile is the Median value = 7


ii)	This boxplot shows the Right Skewed median is towards the left side it is not normal distribution.


iii)	In that case there would be no Outliers on the given dataset because of the Outlier data had a positive skewness it will reduce and the data will be a normal distribution


3.
![image](https://github.com/HemalathaVel/Statistics-Level-2/assets/154992818/08706adb-64c0-4b65-8ed6-71e6e83f97fc)


**Answer the following three questions based on the histogram above.
(i)	Where would the mode of this dataset lie?
(ii)	Comment on the skewness of the dataset.	
(iii)	Suppose that the above histogram and the box-plot in question 2 are plotted for the same dataset. Explain how these graphs complement each other in providing information about any dataset.**


Ans: 
i)	 The mode of this dataset lies between 5 to 10 we can say it by   approximately between 4 to 8.


ii) 	The skewness of data is right-skewed.  Mean>Median>Mode.


iii)	 They both are right skewed and both have outliers.  The median can be easily visualized in the box plot where as in histogram mode is more visible.


**4. AT&T was running commercials in 1990 aimed at luring back customers who had switched to one of the other long-distance phone service providers. One such commercial shows a businessman trying to reach Phoenix and mistakenly getting Fiji, where a half-naked native on a beach responds incomprehensibly in Polynesian. When asked about this advertisement, AT&T admitted that the portrayed incident did not actually take place but added that this was an enactment of something that “could happen.” Suppose that one in 200 long-distance telephone calls is misdirected. What is the probability that at least one in five attempted telephone calls reaches the wrong number? (Assume independence of attempts.)**


Ans: 
   To find the probability that at least one in five attempted telephone calls reaches the wrong number, we can use the complement rule:
 P (at least one in five is wrong number) = 1 – P (none in five is wrong)
 Probability of call directly connected:
  P (directed correctly) = 1 – 1/200
                         = 199/200
The probability for at least one in five attempted telephone calls reaches the wrong number:
Number of calls = 5 n = 5 p 
                = 1/200
P(x) = At least one in five attempted telephone calls reaches the wrong number
 P (x) = (nCx) (p^x) (q^n-x)
 P (1) = (5C1) (1/200) ^1 (199/200) ^5-1
P (1) = 0.025


**5.	Returns on a certain business venture, to the nearest $1,000, are known to follow the following probability distribution**

x	P(x)
-2,000	0.1
-1,000	0.1
0	0.2
1000	0.2
2000	0.3
3000	0.1


**i)	What is the most likely monetary outcome of the business venture?
(ii)	Is the venture likely to be successful? Explain
(iii)	What is the long-term average earning of business ventures of this kind? Explain
(iv)	What is the good measure of the risk involved in a venture of this kind? Compute this measure**


Ans: 
i)	The most likely monetary outcome of the business venture is $2000.
As for $2000 the probability is 0.3 which is maximum as compared to others.  


ii)	Yes, the probability that the venture will make more than 0 or a profit.
P(x>0) + P(x>1000) + P(x>2000) + P(x=3000) = 0.2+0.2+0.3+0.1
                                           = 0.8
In this state that there is a good chance for this venture to be making a profit as 80%.


iii)	The long-term average is Expected value = Sum (X*P(X))
                                              = (-200×0.1) + (-1000×0.1) + (0×0.2) + (1000×0.2) + (2000×0.3) + (3000×0.1)
                  E = -200 - 100 + 0 + 200 + 600 + 300
                  E = 800
The long-term average earning if business ventures of this kind is $800


iv)	The good measure of the risk involved in a venture of this kind depends on the Variability in the distribution.
Higher Variance means more chance of risk
One common measure of risk is the standard deviation.
The formula for the standard deviation (σ) of a probability distribution is 
   σ = sqrt (∑(x-E) ^ 2 * P(x))
 Where:
 x = each possible outcome
E = expected value (calculated in part iii)
P(x) = probability of each outcome

Probability distribution:
   σ = sqrt [∑ (x – 800) ^2 * P(x)] 
   σ = sqrt [((-2000 - 800) ^ 2 * 0.1) + ((-1000 - 800) ^ 2*0.1) + ((0 - 800) ^2*0.2) + ((1000 - 800) ^2 *0.2) + ((2000 – 800) ^2 *0.3) + ((3000 – 800) ^2 *0.1)] 
  σ = sqrt [(1200^2 * 0.1) + (200^2 *0.1) + (800^2 *0.2) + (200^2 *0.2) + (1200 ^ 2 *0.3) + (2200 ^ 2 * 0.1)]
  σ = sqrt [14400 + 4000 + 128000 + 8000 + 432000 + 484000]
     = sqrt [1070400]
 σ ≈ 2234
So, the standard deviation (a measure of risk) of this venture is approximately $2,234. 



























