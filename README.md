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
 Include the necessary coding and corresponding screenshots
 

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=[2018,2019,2020,2021,2022]

y=[15000,20000,25000,30000,35000]

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.title('2D Diagram')

plt.show()

<img width="889" height="683" alt="image" src="https://github.com/user-attachments/assets/811e3800-3e99-44c7-887b-6d7793050d07" />

plt.subplot(2,2,1)

plt.plot(x,y,'r--')

plt.subplot(2,2,2)

plt.plot(x,y,'g--')

plt.subplot(2,2,3)

plt.plot(x,y,'bo')

plt.subplot(2,2,4)

plt.plot(x,y,'go')

<img width="879" height="673" alt="image" src="https://github.com/user-attachments/assets/9084846b-a7a6-4eef-813f-2b5858bca573" />

x=np.arange(0,4*np.pi,0.1)

y=np.sin(x)

plt.title("sine wave form")

plt.plot(x,y)

plt.show()

<img width="853" height="661" alt="image" src="https://github.com/user-attachments/assets/abcb599e-f724-45f3-bc8a-3cb8d67ddb2b" />

x=[2,8,10]

y=[11,16,9]

x1=[3,9,11]

y1=[6,15,7]

plt.bar(x,y,color='r')

plt.bar(x1,y1,color='g')

plt.title("Bar graph")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show(_)

<img width="835" height="669" alt="image" src="https://github.com/user-attachments/assets/995b0431-67e6-4ed5-a3e3-ad5e25636a95" />

x=[1,2,3]

y=[7,3,9]

plt.plot(x,y,color='g')

plt.title("my first graph")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show()

<img width="823" height="677" alt="image" src="https://github.com/user-attachments/assets/2e12467a-aa74-4cb0-87b6-54187d408357" />


x1=[1,2,3]

y1=[2,4,1]

plt.plot(x1,y1,label='line1')

x2=[1,2,3]

y2=[4,1,3]
plt.plot(x2,y2,label='line2')

plt.title('This is multi-line raph means two lines are same')

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.legend()

plt.show()

<img width="837" height="663" alt="image" src="https://github.com/user-attachments/assets/59ca44d7-944c-4b7b-a701-267b55dfea13" />

x=[1,2,3,4,5,6]

y=[2,4,1,5,2,6]

plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='red',markersize=12,label='spices')

plt.ylim(1,8)

plt.xlim(1,8)

plt.title('Line graph')

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.legend()

plt.show()

<img width="833" height="673" alt="image" src="https://github.com/user-attachments/assets/9390309a-9c76-4f90-a4a8-236b3ec078cb" />

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]

plt.plot(yield_apples,linestyle='dashed',linewidth=3,marker='*',markersize=12,color='green')

plt.show()

<img width="843" height="615" alt="image" src="https://github.com/user-attachments/assets/3543dc24-2f30-4118-9245-0ddf0b28e8e9" />

oranges=[2,4,6,7,8,12,45]

apples=[2,4,5,6,8,23,37]

years=[2019,2020,2021,2022,2023,2024,2025]

plt.plot(years,apples,marker='o')

plt.plot(years,oranges,marker='*')

plt.title("crop yields in kanto")

plt.xlabel('Years')

plt.ylabel('Yield(tons per hectare)')

plt.legend(['apples','oranges'])

plt.show()

<img width="827" height="669" alt="image" src="https://github.com/user-attachments/assets/eb1a62de-23a2-4b6a-ba48-087d220b5716" />

oranges=[2,4,6,7,8,12]

apples=[2,4,5,6,8,23]

years=[2019,2020,2021,2022,2023,2024]

plt.bar(oranges,apples)

plt.plot(years,apples,label='apples',marker='*')

plt.plot(years,oranges,label='oranges',marker='o')

plt.title("Fruit sales")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.legend()

plt.show()

<img width="831" height="663" alt="image" src="https://github.com/user-attachments/assets/568269a1-781d-43c5-adec-140af6c7c781" />

plt.figure(figsize=(12,6))

plt.plot(years,oranges,marker='o',label='oranges')

plt.title("Yield of oranges(tons per hectare)")

plt.legend()

<img width="1333" height="745" alt="image" src="https://github.com/user-attachments/assets/381f4653-32d3-44bd-869d-e23d890b33db" />

print("scatter plot is:")

x=[1,2,3,4,5,6,7,8,9,10]

y=[2,4,5,7,6,8,9,11,12,12]

plt.scatter(x,y,label='star',color='green',marker='*',s=30)

plt.title("my scatterplot!")

plt.xlabel("x-axis")

plt.ylabel("y-axis")

plt.legend()

plt.show()

<img width="771" height="649" alt="image" src="https://github.com/user-attachments/assets/72723158-8091-41f7-9894-9f647e7dff57" />


x=[1,2,3,4,5]

y1=[10,12,14,16,18]

y2=[5,7,9,11,13]

y3=[2,4,6,8,10]

plt.fill_between(x,y1,color='green',label='y1')

plt.fill_between(x,y2,color='blue',label='y2')

plt.fill_between(x,y3,color='red',label='y3')

plt.title("fill between is")

plt.legend()

plt.show()

<img width="827" height="647" alt="image" src="https://github.com/user-attachments/assets/5111567c-de25-4beb-9e20-146da27ff5cc" />

plt.stackplot(x,y1,y2,y3,labels=['line1','line2','line3'])

plt.legend(loc='upper left')

plt.title("stacked line chart")

plt.xlabel('x-axis')

plt.ylabel('y-axis')

plt.show()

<img width="831" height="671" alt="image" src="https://github.com/user-attachments/assets/0ad8ba4b-9712-4446-9525-463219f2efd0" />

import numpy as np

import matplotlib.pyplot as plt

from scipy.interpolate import make_interp_spline

x=np.array([1,2,3,4,5,6,7,8,9,10])

y=np.array([2,4,5,7,8,9,10,11,12,13])

spl=make_interp_spline(x,y)

x_smooth=np.linspace(x.min(),x.max(),100) # Changed linespace to linspace

y_smooth=spl(x_smooth)

plt.plot(x,y,'o',label='data')

plt.plot(x_smooth,y_smooth,'-',label='spline')

plt.legend()

plt.show()

<img width="809" height="599" alt="image" src="https://github.com/user-attachments/assets/ad6cf831-3eac-441c-9832-2e7168900895" />

values=[5,6,7,3,2]

names=['A','B','C','D','E']

plt.bar(names,values,color='green')

plt.show()

<img width="793" height="615" alt="image" src="https://github.com/user-attachments/assets/e3ffac6b-943f-4acb-b661-685e2f9211e0" />

ages=[2,5,70,40,45,50,43,40,44,60,7,13,57,18,90,77,32,21,20,40]

range1=(0,100)

bins=10

plt.hist(ages,bins,range1,color='green',histtype='bar',rwidth=0.8)

plt.xlabel('ages')

plt.ylabel('no.of people')

plt.title('my histogram')

plt.show()

<img width="765" height="675" alt="image" src="https://github.com/user-attachments/assets/f2e8c3eb-c7d4-40ac-9d72-bc477db718d9" />

x=[2,1,6,2,4,8,9,4,2,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x,bins=10,color='green',alpha=0.5)

plt.show()

<img width="799" height="605" alt="image" src="https://github.com/user-attachments/assets/669b44d1-e12c-4426-9b23-78138eb1c090" />

np.random.seed(0)

data=np.random.normal(loc=0,scale=1,size=100)

data

<img width="879" height="547" alt="image" src="https://github.com/user-attachments/assets/06c804ab-05bf-4e97-9512-dcbcee9fa0db" />

fig,ax=plt.subplots()

ax.boxplot(data)

ax.set_xlabel('x-axis')

ax.set_ylabel('y-axis')

ax.set_title('box plot')

<img width="857" height="719" alt="image" src="https://github.com/user-attachments/assets/b8ff35f0-0f5f-4f9c-b80f-ca119fc2571a" />

activities=['eat','sleep','work','play']

slices=[3,7,8,6]

colors=['r','y','g','b']

plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

<img width="631" height="589" alt="image" src="https://github.com/user-attachments/assets/2b31b0b6-53a8-4aed-8de6-493ae9e4118e" />

labels='python','C+','ruby','java'

sizes=[215,130,245,210]

colors=['gold','yellowgreen','lightcoral','lightskyblue']

explode=(0,0.4,0,0.5)

plt.pie(sizes,explode=explode,colors=colors,labels=labels,autopct='%1.1f%%',shadow=True)

plt.axis('equal')

plt.show()

<img width="759" height="575" alt="image" src="https://github.com/user-attachments/assets/6effb534-f37d-4c61-a8fb-d24f1c9fac62" />



# Result:
Thus , all te data visualization techniques of matplotlib has been implemented successfully.


