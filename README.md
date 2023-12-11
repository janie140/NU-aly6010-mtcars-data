# NU-aly6010-mtcars-data

Introduction 
The mtcars data present fuel consumption and 10 aspects of automobile design and performance for 32 car models. Here below are the data dictionary and the head rows of this dataset. 
 
Table 1: Data Dictionary 	 
 
 
Hypothesis Testing 
#Right-tailed t-test for the mean weight (1000 lbs.) of the cars 
H0: Mean weight (wt) = 3.0 
H1: Mean weight (wt) > 3.0 
CI: 95%,  = 0.05 
 
 
The right-tailed t-test yields a p-value of 0.1092, which is greater than the significance level () of 0.05. Thus, we do not have enough evidence to reject the null hypothesis, meaning we cannot conclude that the mean weight of the cars is greater than 3 (*1000 lbs). The sample mean weight is 3.21725, and the 95% confidence interval for the mean is (2.923979, Inf). 
#Two-tailed t-test for mean qsec (Fastest time to travel 1/4 mile from standstill (in seconds)) 
H0: Mean qsec = 19 
H1: Mean qsec  19 
CI: 99%,  = 0.01 
 
 
The two-tailed t-test yields a p-value of 0.0009706, which is considerably less than the significance level () of 0.01. Hence, we reject the null hypothesis and conclude that the mean ¼ mile time of the cars is different from 19. As we can see, the sample mean qsec is estimated at 17.84875, and the 99% confidence interval for the mean is (16.98193, 18.71557). 
#Left-tailed t-test of mean disp (engine displacement in cubic inches) 
H0: Mean disp = 250 
H1: Mean disp  < 250 
CI: 95%,  = 0.05 
 
 
With a p-value of 0.1928, we fail to reject the null hypothesis at the 0.05 significance level (0.1928 > 0.05). Therefore, we do not have enough evidence to conclude that the population mean of the displacement variable is less than 250 cubic inches. The mean of the sample is 230.7219 cubic inches, and the 95% confidence interval for the population mean is (-Inf, 267.8698). We would need more data or a different test to draw a stronger conclusion. 
Conclusion 
Based on the results of the above t-tests, we can summarize that there is insufficient evidence to support the claims that the average weight of cars is greater than 3000 lbs. and that the mean engine displacement is less than 250 cubic inches, with a confidence level of 95%. However, we can conclude with 99% confidence that the mean of the fastest time to travel a quarter mile from a standstill is not equal to 19. 
![image](https://github.com/janie140/NU-aly6010-mtcars-data/assets/121474131/6fe3c28f-2c93-4b86-9592-d04dd2195c12)
