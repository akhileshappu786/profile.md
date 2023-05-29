# SELF INTRODUCTION
## AKHILESH P.
AKHILESH P.
1.  07/08/2006
2. E-MAIL ID:akhileshpct22@gpcchelakkara.ac.in
3. PH NO:8891657523
```

I am Akhilesh P, hailing from Vaniyamkulam. I successfully completed my 10th-grade education at THS Shoranur, where I gained a solid foundation in academics. Currently, I am pursuing a diploma in computer engineering at GPC Chelakkara, which signifies my passion for the world of technology.

Embarking on the path of computer engineering is an excellent choice, as it opens up a realm of opportunities in the ever-evolving field of technology. With each passing day, advancements in computer engineering present innovative solutions and shape the future of our digital world. I am confident that through my studies at GPC Chelakkara, I will gain the knowledge and skills necessary to contribute meaningfully to this exciting industry.

During my educational journey, I have developed a keen interest in various aspects of computer engineering, such as programming languages, hardware design, software development, and networking. I am driven by a curiosity to explore the intricacies of these subjects, eager to unravel their mysteries and apply my learning to real-world scenarios.

Outside of my academic pursuits, I am an avid learner who enjoys staying up-to-date with the latest technological advancements and trends. This allows me to broaden my understanding of the ever-changing digital landscape and discover new possibilities for innovation.

As I progress in my studies and further hone my skills, I look forward to leveraging my knowledge to make a positive impact in the field of computer engineering. Whether it's developing cutting-edge software, optimizing system performance, or solving complex technical challenges, I am eager to contribute my abilities and collaborate with like-minded individuals to push the boundaries of what is possible.

I am excited to be a part of this technological era and witness firsthand the transformative power of computer engineering. Feel free to reach out to me if you have any questions or if there's anything specific you'd like to discuss regarding computer engineering or any related topics.

Wishing you all the best in your educational journey and future endeavors!

Warm regards,
Akhilesh.p
```
# PROGRAMS  STUDIED
- PYthon coding
- PYthon mmachine learning

# ONLINE COMPILER
- GOOGLE COLAB
- HACKERSRANK
- w3 school


# programs
```
- import numpy as np
arr=np.array((1,2,3,4,5))
print(arr)
```
```
- import re
pattern='^a...s$'
test_string=input("enter a string")
result=re.match(pattern,test_string)
if result:
  print("search succesfull.")
else:
  print("search unsuccesfull.")
```
```
- import re
string='twelve:12 eight nine:89.'
pattern='\d+'
result=re.split(pattern,string)
print(result)
```
```
- import matplotlib.pyplot as plt
import numpy as np
y=np.array([35,25,25,15])
plt.pie(y)
plt.show()
```
```
- import matplotlib.pyplot as plt
import numpy as np
y=np.array([35,20,15,40])
mylabels=["Apples","Banannas","Cherries","Dates"]
plt.pie(y,labels=mylabels,startangle=90)
plt.show()
```
```
- import matplotlib.pyplot as plt
import numpy as np
#plot 1:
```
```
- import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('my first graph!')
plt.show()
```
```
- import matplotlib.pyplot as plt
x=[2,2,2]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('my first graph!')
plt.show()
```
```
- import matplotlib.pyplot as plt
import numpy as np
x=np.linspace(1,5)
y=x**3
fig=plt.figure()
plt.plot(x,y,'r')
plt.show()
```
```
- from matplotlib import pyplot as plt
Names=['Arun','James','Ricky','Patrick']
Marks=[51,87,45,67]
plt.bar(Names,Marks,color='blue')
plt.title('Result')
plt.xlabel('Names')
plt.ylabel('Marks')
plt.show()
```
```
- import matplotlib.pyplot as plt
left=[1,2,3,4,5]
height=[10,24,36,40,5]
tick_label=['one','two','three','four','five']
plt.bar(left,height,tick_label=tick_label,width=0.8,color=['red','green'])
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart')
plt.show()
```
```
- import matplotlib.pyplot as plt
ages=[2,5,70,40,56,40,56,33,22,12,34,12,34,33,56,88,67,88,67,65,45,68,23]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no.of people')
plt.title('my.histogram')
plt.show()
```
```
- import matplotlib.pyplot as plt
import numpy as np
x=np.array([5,7,8,7,2,17,2,9,4,11,12,9,6])
y=np.array([99,86,87,88,111,86,103,87,94,78,77,86,85])
plt.scatter(x,y)
plt.show()
```
```
- import pandas as pd 
df=pd.read_csv('/exams.csv')
print(df)
```
```
- df.head()
```
```
- df.head(10)
```
```
- df.tail(5)
```
```
- import numpy as np
from sklearn.svm import SVC
x=np.array([[-1,-1],[-2,-1],[1,1],[2,1],])
y=np.array(['boy','boy','girl','girl'])
ml=SVC()
ml.fit(x,y)
result=ml.predict([[-1,-1]])
print(result)
```
```
- import numpy as np
from sklearn.svm import SVC
from sklearn.datasets import load_iris
iris=load_iris()
x=iris.data
y=iris.target
ml=SVC()
ml.fit(x,y)
result=ml.predict([[6.3,3.3,6.0,2.5]])
print(result)
```
```
