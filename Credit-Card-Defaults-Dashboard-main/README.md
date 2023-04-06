# Credit Card Defaults Dashboard

![image](https://user-images.githubusercontent.com/54328466/180609456-32c6b9da-0cd7-48a7-9a32-4e39c8617bb9.png)
 
This dashboard has been created using d3.js v7.

Introduction:

The dashboard presents a visual analysis of default payments of credit card holders. The data consists of basic details of each individual and these have been used to build the dashboard. This dataset contains details of different individuals from Taiwan. The same dashboard can be implemented by any bank to gain insights about their defaulting customers.
There are six major graphs that are present in the dashboard. The four graphs on the top depict the number of defaulters across different age groups, gender, marital statuses and education levels. The other two graphs analyze the distribution of limiting balance of the defaulters and the payment made for bill amounts in the past six months.


Interactivity:

The dashboard is made user interactive by providing filtering and mouse over options. The dashboard can be filtered by different attributes such as education level, marital status, gender and age group of the defaulters. Filtering can be done by clicking on the bar or element that corresponds to that value and the dashboard refreshes to display the new data. Multiple levels of filtering can be done by selecting elements from different graphs and the data displayed gets more specific to those values. The ‘Reset Filters’ button on the top right of the dashboard brings back the dashboard to its original state. The exact value of each element that is plotted on the graph, can be known by hovering the mouse over the element. The value is printed next to the element.  

Critical analysis of graphs: 

Looking into each graph in the dashboard, we can analyze the most prevalent characteristics of the defaulters. 
The ‘defaulters by education level’ graph shows the level of education received by the defaulters.  There are four levels in the dataset and here, this graph depicts that university graduates are most likely to default. Around 50% of the total defaulters lie in this category. 
The ‘defaulters by marital status’ graph tells us about the marital status of these defaulters. Here the graph indicates that people who are single have more chances of defaulting. However, the number of married people who default is also close enough. 
Moving to the ‘defaulters by gender’ graph, we can see the number of male and female defaulters present. We observe that females have a higher chance of defaulting when compared to males. Around 57% of the defaulters are females.
All the individuals have been put into different age groups and plotted on the ‘defaulters by age group’ graph. This graph shows that the age groups of 20-29 and 30-39, i.e., the mid aged individuals, have the highest number of defaulters with slightly more numbers in the thirties group. We can also observe that as the age group increases, the defaulting reduces.
The limiting balance of these defaulters is analyzed through a histogram, which gives the amount of the given credit for the individual as well as supplementary cards of the family members. Here we observe that these values are slightly skewed and a greater number of individuals have a balance between 0 and 200,000 which is where the peak of the histogram lies. 
The billing amount vs payment graphs indicate the bill amount and the corresponding payment done by each individual for the last six months. Here we observe that for majority of the individuals, the bill amount is very high but the payment done by them is low. This is inferred as a large number of points are placed close to zero on the x axis.  

Insights:

It can be observed that the highest number of defaulters are females. Filtering the dashboard for females, we can observe that the majority defaulters are aged 20-29 and them being university graduates. 

![image](https://user-images.githubusercontent.com/54328466/180609480-e3778e6f-e3aa-4724-a766-525c5b06b093.png)

Likewise, filtering the dashboard for university graduates or filtering for the age group of 20-29 gives us similar results.

Considering the age group that contains the highest number of individuals i.e., 30-39, and filtering the dashboard for these values shows females again toping the charts and majority being university graduates.
 
![image](https://user-images.githubusercontent.com/54328466/180609496-c4de537c-d8ed-4750-b40f-e988ee7e2125.png)

However, in both the above cases, marital status has not been of much significance. Nearly similar number of married and unmarried individuals are present. 

Filtering the dashboard for married individuals, we obtain the highest numbers among the ages of 30 to 50. 

![image](https://user-images.githubusercontent.com/54328466/180609509-3562f9ef-45f9-4a0f-91bd-d1f9a86b17cc.png)

Filtering for unmarried individuals, we obtain the highest number of individuals in the age group 20-29.
 
![image](https://user-images.githubusercontent.com/54328466/180609510-da3484aa-f2bb-433a-94ed-2a78888d3244.png)

Another major insight obtained from this analysis is that females in the age group of 20-29 have the higher number of defaulters when compared males in all the age groups.
The dashboard image below shows the number of female defaulters in the twenties age group. (1408).

![image](https://user-images.githubusercontent.com/54328466/180609517-997160a4-b606-4b20-889c-a23ee6841c17.png)
 
The dashboard image below shows the number of males in all the age groups where the maximum number is 1050 in the age group of thirties. This is lesser than the number of females in the above filtered dashboard.
 
![image](https://user-images.githubusercontent.com/54328466/180609524-c494879b-b596-45c6-a62e-3416d4b79a01.png)

In general, we can observe that females have a higher tendency to default when compared to males. 


