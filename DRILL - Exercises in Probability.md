### 1. Calculate the probability of flipping a balanced coin four times and getting each pattern: HTTH, HHHH and TTHH.

HTTH - this pattern can occur once out of 16 events so, probability is 1/16 = 0.0625

HHHH - same as above. Can only occur once out of 16 events so, probability is 1/16 = 0.0625

TTHH - This pattern too can occur once so, probability is 1/16  = 0.0625

### 2. If a list of people has 24 women and 21 men, then the probability of choosing a man from the list is 21/45. What is the probability of not choosing a man?

It should be 1 - 21/45 = 0.53 or just choosing women which is 24/45 = 0.53

### 3. The probability that Bernice will travel by plane sometime in the next year is 10%. The probability of a plane crash at any time is .005%. What is the probability that Bernice will be in a plane crash sometime in the next year?

Probability of Travel is 10% = 0.10

Plance crash probability is .005% = 0.00005

The total probability is = 0.1 * 0.00005 = 0.000005

### 4. A data scientist wants to study the behavior of users on the company website. Each time a user clicks on a link on the website, there is a 5% chance that the user will be asked to complete a short survey about their behavior on the website. The data scientist uses the survey data to conclude that, on average, users spend 15 minutes surfing the company website before moving on to other things. What is wrong with this conclusion?

User click and Survey probability - 5% = 0.05

Average user spend = 15 minutes

It seems there is no relationship between Survey and the average time spending. The Survey comes only for 0.05 % for the user which is 5 i 100 users so this is not a right data to find the average timing spend on the website.


--------- Given ----------
Person Suffering and result is +ve = 98%

Person is not Suffering and result is +ve = 10%

Population Sufferer is = 0.05%

---------- Derived ----------

1. 0.5% of having Th (99.5% doesn't have Th)

2. 98% gives pos result when Th is there (means 2% is miss)

3. 10% given postive when its not there (means 90% gives correct result)

Th (0.5% = 0.005)
No Th (99.95% = 0.9995)

Test Pos (having Th - true pos) - 0.05% * 98% = 0.00049

Test Pos (having no Th) - 10% * 99.95% = 0.0999

Test Neg (having Th) - 2% * 0.5% 

Test Neg (having no Th)


na| Th(0.5%)|No Th(99.5%)
---|---|---
Test pos |(0.005*0.98) = 0.0049|(0.995*0.1)=0.0995
Test Neg|0.0001|90% * 99.5% = 0.8955


1. Be Positive = 0.0049 + 0.0995 = 0.1044

2. Correctly diagnose a sufferer of Thripshaw's = 0.98 ~ 98%

3. Correctly identify a non-sufferer of Thripshaw's = 0.9 ~ 90% which is false negative

4. Misclassify the person - 0.0995 + 0.0001 = 0.0996 (Test po + No Th and Test Neg + Th)


