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
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
```
![o1](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/988bdaf1-9800-45c1-8974-413fb7b56349)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customization')
plt.show()
```

![o2](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/03fe138e-0d2f-4fd5-bc56-37cd1759149e)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

![o3](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/2952da58-908e-415c-8bd4-8e5ee3ff70c6)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```

![o4](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/2dbcbe6e-0383-494c-b730-24ffdcd2655f)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('year')
plt.ylabel('yield(tons per hectare)');
plt.title("Crop yields in kanto")
plt.legend(['Apples','Oranges']);
```

![o5](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/a90bce2f-ef6f-4e25-a3b1-1c01aa14ce80)


```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('year')
plt.ylabel('yield(tons per hectare)');
```

![o6](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/2e7d6b66-ca12-4cd6-95b6-9d0761842145)

```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("yield of oranges(tons per hectare)");
```

![o7](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/950aaf0c-126f-4c5f-8c36-c8db9510c247)

```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('year')
plt.ylabel('yield (tons per hectare)')
plt.title("Crop yields in kanto")
plt.legend(['Apples','Oranges'])
```

![o8](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/6e0890bf-8f82-4931-81dc-240ef0729cbb)

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```

![o9](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/6666bad3-93f8-4f75-9888-356796ca30f0)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```

![o10](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/14a4612f-2f9c-4787-8de8-9fd3f7b35431)

```
y
```

![o11](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/98d6216e-4252-4e4c-a0d3-f970384a1069)

```
plt.scatter(x,y,c='r')
plt.xlabel('x axis')
plt.ylabel('y label')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```

![o12](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/4c33f54c-6b29-4505-8d40-88bd19064723)

```
y=x*x
y
```

![o13](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/612b26d8-d1ea-48eb-8f8a-658c136ff093)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('y label')
plt.title('2d Diagram')
```

![o14](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/0065e73f-7ddb-43a9-9987-4b023fee7a34)

```
np*pi
```

![o15](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/a3d70eb4-992b-49b3-874d-1a76c27d7a43)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![o16](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/d4e77a3a-bafa-48a3-b75e-56f5638cd009)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```

![o17](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/1198f99b-f148-4fe2-949d-e53eef9e68fd)

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

![o18](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/9b0ca420-397a-4d1e-a97c-a06f15622def)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('y axis')
plt.xlabel('x axis')
plt.show()
```

![o19](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/0d5ad808-9081-48fc-a3d8-d84826e74dce)

#Histogram
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```

![o20](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/1d893d06-e2e6-418a-a5df-5ca236e8cfd5)

#Box plot
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```

![o21](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/cd23efce-9b99-4c27-a56c-8ffc99fb7345)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('values')
ax.set_title('Box plot')
```

![o22](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/39d88aec-91ab-4612-ad93-a0a75fe26880)

#Piechart
```
labels='python','c++','Ruby','java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%'  ,shadow=True)
plt.axis('equal')
plt.show()
```

![o23](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/77248690-441f-409d-9d52-ebd00ab6de5e)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```

![o24](https://github.com/chgeethika/EXNO-5-DS/assets/142209368/9d60e5fa-11eb-4f21-9221-a657f6f2ca59)







# Result:
          To Perform Data Visualization using matplot python library for the given datas issuccessful.
