# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

marks = [13, 45, 63, 78]
student = ['ABC', 'QOR', 'EFB', 'TOB']
plt.plot(student, marks)
plt.xlabel('Student name')
plt.ylabel('Marks')
plt.show()
```

<img width="1054" height="664" alt="image" src="https://github.com/user-attachments/assets/85178d04-9f52-4bdb-9af1-5f0e12fbe8e4" />

```
x = [10, 20, 30, 40, 50]
y = [100, 200, 300, 400, 500]
plt.scatter(x, y, label='stars', color='green', marker='*', s=30)
plt.legend()
plt.show()
```

<img width="746" height="527" alt="image" src="https://github.com/user-attachments/assets/cb399e17-5431-426a-9cc7-328f100c3843" />

```
act = ['eat', 'sleep', 'work', 'play']
slices = [3, 7, 8, 6]
color = ['r', 'y', 'g', 'b']
plt.pie(slices, labels=act, colors=color, startangle=90, shadow=True, explode=(0.1, 0.1, 0.1, 0.1), radius=1.2, autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="1073" height="557" alt="image" src="https://github.com/user-attachments/assets/e8ab53b6-c1f3-46a0-b89b-6f21ff87cba9" />

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1', 'y2'])
plt.show()
```

<img width="771" height="606" alt="image" src="https://github.com/user-attachments/assets/3251e3ac-3d77-4faa-a816-7f3d56f85e42" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1 = ['red', 'green']
c2 = ['b', 'g']
plt.bar(names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="760" height="641" alt="image" src="https://github.com/user-attachments/assets/89a9c803-8ecb-4a07-89b4-f2b05bd542cd" />

```
x = [2, 1, 6, 4, 2, 4, 8, 9, 4, 2, 4, 10, 6, 4, 5, 7, 7, 3, 2, 7, 5, 3, 5, 9, 2, 1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()
```

<img width="764" height="495" alt="image" src="https://github.com/user-attachments/assets/26aee205-a564-451b-8e1e-fb417c1739c2" />

```
np.random.seed(0)
data = np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="717" height="427" alt="image" src="https://github.com/user-attachments/assets/888afa0f-ef5e-44b5-abf7-b480a8ade0e2" />

```
fig, ax = plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
plt.show()
```

<img width="745" height="591" alt="image" src="https://github.com/user-attachments/assets/d85724d6-9d9b-48c6-b8f4-4553cddeb24d" />



# Result:
 Include your result here
