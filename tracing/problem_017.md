**problem**

nums = [2, 5, 8, 1]

total = 0

for n in nums:
    if n > 3:
        total = total + n

print(total)

**my trace**
Loop 1:
n = 2
total = 2 > 3 = False = 0

Loop 2:
n = 5
total = 5 > 3 = True = 5

Loop 3:
n = 8
total = 8 > 3 = True = 5 + 8 = 13

Loop 4:
n = 1
total = 1 > 3 = False = 13

**Final total = 13**

**Output = 13**
