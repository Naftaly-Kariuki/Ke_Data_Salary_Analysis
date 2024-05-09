# The Kenyan Data Market
Analysis of salaries in the Kenyan data market i.e Data Analyst, Data Scientist and Data Engineer
The dataset used in this analysis was obtained from [Phoenix Analytics](https://linktr.ee/phoenixke?fbclid=PAZXh0bgNhZW0CMTEAAabcKbrvs7cG-8INkOa3wxe33wBo-diXFeGOH0qBzZ535N2DoT6RATxTO78_aem_AdRZD3ieTkQSG6IxmnO7-FaHld6YsEI3-mL5erSM2x1wMYribc4Nya7nKqESFD9dgPEIU4ZJMbrLnVN7mI_JXVxq).
The analysis covers data recorded upto the 6th of May 2024.

### Motivation For This Analysis
Data related to salaries are incredbily hard to come by especially for the Kenyan market hence this opportunity was hard to pass by and I hope other people will find it usefull as I have.
With that said, I sought to answer the following;
1. What are the monthly average salaries for different data roles?
2. Are there noticeable differences in salaries among these roles?
3. How do salaries vary based on years of experience?
4. Is there a disparity in salary distribution based on gender?
5. What percentage of data roles in Kenya require Python proficiency?

## Overview
As the data is obtained from an Analytics group, the Data Analysts are understandably the majority and their salaries will assumably be more in line with what is in the market compared to those of data engineers and data scientists, and given more data, the averages of Data Scientists and Data Engineers might significantly change. The "Other" group consists of other data related roles including Business Intelligence Analysts, Business Analysts, Statisticians, Inventory Analysts etc


![Number of Roles](https://github.com/Naftaly-Kariuki/Ke_Data_Salary_Analysis/assets/49984197/850a2b33-6136-494c-91b6-9e3d76b57272)


## Salary Breakdown

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>median</th>
      <th>mean</th>
    </tr>
    <tr>
      <th>Role</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Data Analyst</th>
      <td>94500.0</td>
      <td>109850.000000</td>
    </tr>
    <tr>
      <th>Data Engineer</th>
      <td>205000.0</td>
      <td>193125.000000</td>
    </tr>
    <tr>
      <th>Data Scientist</th>
      <td>80000.0</td>
      <td>131300.000000</td>
    </tr>
    <tr>
      <th>Other</th>
      <td>100000.0</td>
      <td>130153.571429</td>
    </tr>
  </tbody>
</table>
</div>
The median and mean salaries of Data Analysts and Data Scientists are close to each other, however, data engineers have noticeably higher averages.

### Salary Breakdown By Years of Experience

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>median</th>
      <th>mean</th>
    </tr>
    <tr>
      <th>Experience</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Over  7 Yrs</th>
      <td>235000.0</td>
      <td>292500.000000</td>
    </tr>
    <tr>
      <th>Over 5 Yrs</th>
      <td>166000.0</td>
      <td>188777.777778</td>
    </tr>
    <tr>
      <th>1yr-2yrs</th>
      <td>100000.0</td>
      <td>104231.603774</td>
    </tr>
    <tr>
      <th>3yrs-5yrs</th>
      <td>100000.0</td>
      <td>133695.000000</td>
    </tr>
    <tr>
      <th>Beginner</th>
      <td>40000.0</td>
      <td>59929.629630</td>
    </tr>
  </tbody>
</table>
</div>

![Median Salary According To Experience](https://github.com/Naftaly-Kariuki/Ke_Data_Salary_Analysis/assets/49984197/52fb7bb9-b277-4edf-9c2e-4f96f6303d9d)

As is the case in most industries, the salaries get higher as a professional gets more experience

### Salary Distribution According To Role

![Salary Distribution According To Role](https://github.com/Naftaly-Kariuki/Ke_Data_Salary_Analysis/assets/49984197/06bf386c-a097-43f5-924a-911b71cea9e0)

As already mentioned, Data Engineers have a higher median and mean salary compared to the other roles. The remaining three roles have averages that are relatively close to each other, however, the "Other" group has more outliers because the roles are not explicitly defined and contain a few that command very higher salaries including Data Manager and other Data Management roles

### Top 5 and Bottom 5 Salaries By Role

| Role          | Gross Salary (High to Low) | Gross Salary (Low to High) |
|---------------|----------------------------|----------------------------|
| Data Analyst  | 400,000.0                  | 1,000.0                    |
|               | 312,000.0                  | 5,000.0                    |
|               | 310,000.0                  | 15,000.0                   |
|               | 300,000.0                  | 15,000.0                   |
|               | 270,000.0                  | 15,000.0                   |
| Data Engineer | 335,000.0                  | 30,000.0                   |
|               | 280,000.0                  | 65,000.0                   |
|               | 270,000.0                  | 155,000.0                  |
|               | 240,000.0                  | 170,000.0                  |
|               | 170,000.0                  | 240,000.0                  |
| Data Scientist| 450,000.0                  | 35,000.0                   |
|               | 250,000.0                  | 38,000.0                   |
|               | 140,000.0                  | 40,000.0                   |
|               | 130,000.0                  | 70,000.0                   |
|               | 80,000.0                   | 80,000.0                   |
| Other         | 500,000.0                  | 25,000.0                   |
|               | 450,000.0                  | 30,000.0                   |
|               | 375,000.0                  | 35,000.0                   |
|               | 201,500.0                  | 50,000.0                   |
|               | 200,000.0                  | 60,000.0                   |


### Salary Breakdown By Gender
![Salary Distribution Vs Gender](https://github.com/Naftaly-Kariuki/Ke_Data_Salary_Analysis/assets/49984197/74e943a1-0bfe-4749-a568-503f49934f39)

There is not much to separate the two genders, however, the male group has a few outliers on the higher end commanding much bigger salaries than the norm.

### Python Users
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Total_Users</th>
      <th>Use_Python</th>
      <th>Percentage</th>
    </tr>
    <tr>
      <th>Role</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Data Scientist</th>
      <td>10</td>
      <td>10</td>
      <td>100.000000</td>
    </tr>
    <tr>
      <th>Data Engineer</th>
      <td>8</td>
      <td>5</td>
      <td>62.500000</td>
    </tr>
    <tr>
      <th>Other</th>
      <td>35</td>
      <td>17</td>
      <td>48.571429</td>
    </tr>
    <tr>
      <th>Data Analyst</th>
      <td>102</td>
      <td>45</td>
      <td>44.117647</td>
    </tr>
  </tbody>
</table>
</div>

Virtually every data scientist role requires proficiency in Python contrary to slightly less than half the roles in Data Analysis that require the programming language. Data Engineering roles sit in the middle of these two groups with 62 percent of them requiring Python knowledge.
