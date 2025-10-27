# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

## Aim:
  To Perform Data Visualization using matplot python library for the given datas.

## EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

## Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

## Coding and Output:
```
NAME: DAPPILI VASAVI
REG NO: 212223040030
```
```py
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

### Line Plot:

```py
 marks=[23,35,83,98]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[70,95,83,98]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()

```

<img width="783" height="549" alt="image" src="https://github.com/user-attachments/assets/bef348b3-a372-431a-8810-9e2bf546455f" />

<img width="791" height="569" alt="image" src="https://github.com/user-attachments/assets/ffb7c6f8-72df-4907-a145-545816d76b45" />



### Scatter Plot:

```py
x=[15,25,35,45,55]
 y=[105,205,305,405,505]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

<img width="593" height="412" alt="image" src="https://github.com/user-attachments/assets/431e6916-9103-46c0-8d11-b18c2fbebb30" />

<img width="655" height="464" alt="image" src="https://github.com/user-attachments/assets/0203eab4-e424-496c-9d4c-0c1f8fc53669" />



### Pie Chart:

```py
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```


<img width="682" height="433" alt="image" src="https://github.com/user-attachments/assets/025188ef-a718-4aaf-903a-47e4e1eb80fe" />

<img width="641" height="402" alt="image" src="https://github.com/user-attachments/assets/388e0585-7bdf-4b27-831c-1e4685891c1c" />




### Area Chart:

```py
 x = [2, 4, 6, 8, 10]
 y1 = [15, 20, 25, 30, 35]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

<img width="656" height="431" alt="image" src="https://github.com/user-attachments/assets/4f90cc9f-608c-478f-93d2-cd041a0d75de" />




### Bar Chart:

```py
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['blue', 'pink'] 
c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```

<img width="651" height="466" alt="image" src="https://github.com/user-attachments/assets/f8e5f846-b118-4e08-b634-60017f2515c0" />




### Histogram:

```py
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='pink', alpha=0.5)
plt.show()
```


<img width="672" height="425" alt="image" src="https://github.com/user-attachments/assets/e580de76-50f6-4b48-b465-35d393f91dbd" />




### Box Plot:

```py
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="599" height="357" alt="image" src="https://github.com/user-attachments/assets/e0086634-56c9-47d8-b78a-f9e1a9cd402f" />



```py
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="635" height="494" alt="image" src="https://github.com/user-attachments/assets/0bde9e3b-92eb-4a5c-b787-8d8c56893fc3" />





## Result:

Thus, all the data visualization techniques of matplotlib has been implemented.
