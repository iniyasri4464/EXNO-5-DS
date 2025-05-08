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
### Register no-212223230081
### Developed By-INIYASRI S
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/c3cb6266-4b6f-4dad-a8a3-872195bdb47b)
```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
![image](https://github.com/user-attachments/assets/f18e3358-22fa-42fd-8cdf-752d37351811)
```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/63a0037a-6dcb-4fe3-8948-286b2d0c6164)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```
![image](https://github.com/user-attachments/assets/6666c0d1-c693-430c-a17a-a756b9c43d36)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/58625505-5170-42c2-a64f-1641856789f0)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![image](https://github.com/user-attachments/assets/59160e20-7938-4bcc-9bbb-09649b43fdce)
```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![image](https://github.com/user-attachments/assets/0d20e126-2356-4768-a3c9-65565503c211)
```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/3e96fbde-1188-493a-8426-2b28bbd9dae0)
```
plt.plot(years, yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)') # Corrected y-axis label
```
![image](https://github.com/user-attachments/assets/2dd9a7a5-aedb-4403-9656-c8404c8ae1ac)
```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/a9920968-819c-47a7-9f32-18af5fe2d251)

![image](https://github.com/user-attachments/assets/ea88594b-1875-4bc0-b3f0-2c00198eaf0b)
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/74525b6e-7908-4c58-9269-79902f938a8d)
```
import matplotlib.pyplot as plt
x = [1,2,3,4,5,6,7,8,9,10]
y = [2,4,5,7,6,8,9,11,12,12]
plt.scatter (x, y, label= "stars", color="green", marker="*", s=30)
plt.xlabel('x axis')
plt.ylabel('y - axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/56d31b72-a146-48f0-9f28-368dd5883683)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
```
```
import numpy as np

# Use np.range instead of np.range
x = np.range(0, 10)  # Create an array with values from 0 to 9
y = np.range(11, 21) # Create an array with values from 11 to 20
```
```
x
```
![image](https://github.com/user-attachments/assets/9d731f77-ad52-4862-80e4-0640c3335fcf)
```
y
```
![image](https://github.com/user-attachments/assets/38b28828-220d-4cc9-8e5f-c9055c17316b)
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/48b7ca57-c9b0-4b35-8974-ce456c0e7acd)
```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/9e87af1a-2af3-437e-bc30-21a22cd1053a)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/user-attachments/assets/3ba04ab3-4492-4d63-91ce-f6d7ca87864d)
```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4) 
plt.plot(x,y,'go')
```
![image](https://github.com/user-attachments/assets/32e42be8-c435-4d0e-b863-586492fad8fd)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/a6dce5b5-7297-464d-b6ac-a0f3d48ff8e4)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/0f3f3572-1481-4972-bdbb-fb9ed7ad941d)
```
plt.stackplot(x,y1,y2,y3,labels=['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/f9d254bf-62a0-402e-af60-5c764ea7cf50)
```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
y = np.array([2, 4, 5, 7, 8, 8, 9, 10, 11, 12])
spl = make_interp_spline(x, y)
x_smooth = np.linspace(x.min(), x.max(), 100)
y_smooth = spl(x_smooth)
plt.plot(x, y, 'o', label='data')
plt.plot(x_smooth, y_smooth, '-', label='spline')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/e26e9005-6678-4555-8ac0-e6cc18339924)
```
import matplotlib.pyplot as plt
values = [5, 6, 3, 7, 2]
names = ["A", "B", "C", "D", "E"]
plt.bar(names, values, color="green") 
plt.show()
```
![image](https://github.com/user-attachments/assets/8b1ee17f-94b8-4200-981e-726ae75d3d75)
```
import matplotlib.pyplot as plt
values = [5,6,3,7,2]
names = ["A", "B", "C", "D", "E"]
plt.barh (names, values, color="yellowgreen")
plt.show()
```
![image](https://github.com/user-attachments/assets/74b691b3-8b20-4bfc-9c9a-8a7622207f04)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/a003b513-c70e-44b9-a3ea-8c6c34b80260)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/c84789e8-8130-4bec-b4fb-d49d2302824b)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/340363eb-1b23-4d75-8375-75ea5be5488a)
```
import matplotlib.pyplot as plt
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/b6450a24-ddcc-4559-8ca6-6e228c8d1c19)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/f8026681-e56f-4449-a7fe-9029c7bc3219)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot')
```
![image](https://github.com/user-attachments/assets/048dacde-daae-42ac-921f-db7da2a30f66)
```
import matplotlib.pyplot as plt
activities = ['eat', 'sleep', 'work', 'play']
slices = [3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie (slices, labels = activities, colors=colors,
startangle=90, shadow = True, explode = (0, 0, 0.1, 0), radius = 1.2, autopct = '%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/d9a13d4f-1dce-44ff-9228-f6bd7cea0c58)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/44f82b8a-38c1-4ef1-881c-932807da3190)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/user-attachments/assets/0f0a6303-191a-4ce6-893d-9191153f2019)


# Result:
Thus, The implementation of data visualization using matplotlib has been successfully verified.
