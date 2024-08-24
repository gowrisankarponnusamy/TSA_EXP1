### NAME: GOWRISANKAR P
### REG NO: 212222230041
### DATE: 
# Ex.No: 01 PLOT A TIME SERIES DATA

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
## Population:

```AGE
import pandas as pd
import matplotlib.pyplot as plt
file_path = 'MentalHealthSurvey.csv'
data = pd.read_csv(file_path)
mean_sleep = data['age'].mean()
plt.figure(figsize=(10, 6))
plt.plot(data['age'], label='Age', color='blue')
plt.xlabel('Respondent (Sequential Order)')
plt.ylabel('Average AGE')
plt.title('Average Age - Sequential Plot')
plt.legend()
plt.show()

```


# OUTPUT:
## Age:
![image](https://github.com/user-attachments/assets/8d5fee74-b877-4ad0-83f0-e2c457aa196a)

# RESULT:
Thus we have created the Python code for plotting the time series of given data.
