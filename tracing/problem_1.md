**Problem**

nums = [3, 3, 1, 3]

count = 0

for n in nums:
    if n == 3:
        count = count + 1

print(count)

> My Trace:

i = [0 1 2 3]
nums =[3 3 1 3]

loop 1
n=3
count= 0+1=1

loop 2 
n=3
count= 1+1=2

loop 3
n=1
count = 2

loop 4
n=3
count = 2+1=3


### **Final count and Output =3**
