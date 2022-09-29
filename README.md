# Pharmaceutical Testing

This data was pulled from two csv files, "Mouse_metadata.csv" and "Study_results.csv" these csv's were cleaned and merged to look like this:

![2022-09-29 09_48_52-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193049522-e04740d1-a241-48b7-8f77-c0770d980d13.png)

<hr>

The data was then sorted into another dataframe calculating the Average Tumor Volume, Median Tumor Volume, Variance of Tumor Volume, Tumor Volume Standard Deviation, and Tumor Volume Standard Error per drug:

![2022-09-29 10_28_14-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193058940-b1bdd347-027b-46be-888f-1aaad079109f.png)

<hr>

# Charts Created

### Number of mice tested per drug

![2022-09-29 10_31_18-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193059828-0b33064e-8355-44bb-81a6-a6bde2faf0c4.png)

### Gender Pie Chart

![2022-09-29 10_32_00-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193059987-56807109-b8ee-48d7-85d3-c3ff607c10b9.png)

### Tumor Volume Box Plot

![2022-09-29 10_32_59-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193060222-2375cf1e-4b69-4570-b726-ab9ad9933eec.png)

### Treatment Graph of Mouse I509

![2022-09-29 10_33_51-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193060431-be33d978-dd4c-47f7-bc4e-1a3d976555ee.png)

### Correlation Between Weight and Tumor Volume

![2022-09-29 10_35_38-Matplotlib-Challenge_JMcMullanpymaceuticals ipynb at main · john-mcmullan_Matplo](https://user-images.githubusercontent.com/100164773/193060882-8fd64862-8f25-4639-87d3-0298fe94c89c.png)

<hr>

# Observations

1. Propriva data could be untrustworth due to it being the lowest tested out of all the drugs. With all other drugs being tested on over 150 mice it is concerning to see it below 150.
2. Ramicane and Capomulin have the most trustworthy data because they have the most test subjects and the lowest Standard Error and lowest Standard Deviation.
3. With the test subjects of Capomulin there seems to be a strong correlation between the weight of the mouse and the size of the tumor. I would want to start testing on mice within a smaller weight range.
