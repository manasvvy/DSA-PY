**problem**
nums = [8, 3, 6, 1, 4]

count = 0

for n in nums:
    if n < 5:
        count = count + 1

print(count)

**my trace**

Loop 1:
n = 8
Condition = 8<5 False
count = 0

Loop 2:
n = 3
Condition = 3<5 True
count = 0+1=1

Loop 3:
n = 6
Condition = 6<5 False
count = 1

Loop 4:
n = 1
Condition = 1<5 True
count = 1+1=2

Loop 5:
n = 4
Condition = 4<5 True
count = 2+1=3

**Final count = 3**

**Output = 3**
