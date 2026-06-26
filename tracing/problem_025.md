**problem**
nums = [5, 8, 1, 6]

count = 0

for n in nums:
    if n > 4:
        count = count + 1

print(count)

**my trace**

n = [5, 8, 1, 6]

i = [0, 1, 2, 3]

count = 0

Loop 1:
n = 5
condition = 5>4 True
count = 0 + 1 = 1

Loop 2:
n = 8
condition = 8>4 True
count = 1 + 1 = 2

Loop 3:
n = 1
condition = 1>4 False
count = 2

Loop 4:
n = 6
condition = 6>4 True
count = 2 + 1 = 3

**Final count = 3**

**Output = 3** 
