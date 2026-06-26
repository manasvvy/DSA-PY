**problem**
nums = [9, 2, 7, 4]

smallest = nums[0]

for n in nums:
    if n < smallest:
        smallest = n

print(smallest)

**my trace**

n = [9, 2, 7, 4]

i = [0, 1, 2, 3]

smallest = 9

Loop 1:
n = 9 
9<9 False
smallest = 9

Loop 2:
n = 2
2<9 True
smallest = 2

Loop 3:
n = 7
7<2 False
smallest = 2

Loop 4:
n = 4
4<2 False
smallest = 2

**Final smallest = 2**

**Output = 2**
