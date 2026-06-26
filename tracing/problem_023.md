**problem**
nums = [6, 1, 8, 3]

largest = nums[0]

for n in nums:
    if n > largest:
        largest = n

print(largest)
**my trace**
**my trace**

n = [6,1,8,3]
i = [0 1 2 3]

largest = 6

Loop 1:
n = 6 
6>6 False
largest = 6

Loop 2:
n = 1
1>6 False
largest = 6

Loop 3:
n = 8
8>6 True
largest = 8

Loop 4:
n = 3
3>8 False
largest = 8

**Final largest = 8**

**Output = 8**
