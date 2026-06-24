**problem**
nums = [10, 2, 7, 1]

total = 0

for n in nums:
    if n < 5:
        total = total + n

print(total)

**my trace**
Loop 1:
n =10
10<5 False
total = 0

Loop 2:
n = 2
2<5 True
total = 0+2=2

Loop 3:
n = 7
7<5 False
total = 2

Loop 4:
n = 1
1<5 True
total = 2+1=3

**Final total = 3**

**Output = 3**
