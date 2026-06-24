**problem**
nums = [2, 7, 4, 9]

total = 0

for n in nums:
    if n % 2 == 1:
        total = total + n

print(total)

**my trace**

Loop 1:
n = 2
2 % 2 = 0
False
total = 0

Loop 2:
n = 7 
7 % 2 = 1
True
total = 0 + 7 = 7

Loop 3:
n = 4
4 % 2 = 0
False
total = 7

Loop 4:
n = 9
9 % 2 = 1
True
total = 7 + 9 = 16
**Final total = 16**

**Output = 16**
