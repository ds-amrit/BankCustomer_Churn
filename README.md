# BankCustomer_Churn
GOAL:  Predicting the bank customer's churn status using machine learning models.

![image](https://user-images.githubusercontent.com/107737679/189734204-efffe43a-7b4c-4b11-91cc-f6343ce4e3e6.png)


The basic dataset  project a customer churn rate of 20%.
Given that 20% is a relatively tiny percentage, we must make sure that the model we choose
can accurately predict this 20%, as the bank is more interested in locating and retaining 
this group than it is in precisely predicting the clients who are retained.

Performing Bi-variate categorical analysis using countplots:

![image](https://user-images.githubusercontent.com/107737679/189735660-cfc67cb1-177b-45a9-93d4-c605897821e7.png)


Observations from the data:
1. The vast majority of the data comes from French citizens. 
However, the percentage of churned customers is inversely correlated to the number of customers,
suggesting that the bank may be experiencing difficulties (possibly due to inadequate customer service resources)
in areas where it has fewer customers.

2. Additionally, a higher percentage of women than men leave the bank.

3. It's interesting that customers who use credit cards make up the majority of churning customers, this might just be a coincidence.

4. Unsurprisingly, the churn rate is higher among inactive members. 
Worryingly, the bank may need to implement a programme to make this group active 
given that the overall percentage of inactive members is quite high.

Performing Bi-variate Numerical analysis using boxplots:

![image](https://user-images.githubusercontent.com/107737679/189735196-a0befbc7-2578-4f64-a980-311c1a9bfc05.png)


Machine Learning Models used and their scores on test data:
![image](https://user-images.githubusercontent.com/107737679/189757001-8d48ae89-3aec-4071-962c-f8e48da1a408.png)







