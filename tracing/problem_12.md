**problem**
nums = [4, 7, 2, 9]

largest = nums[0]

for n in nums:
    if n > largest:
        largest = n

print(largest)

**my trace**

nums=[4, 7, 2, 9]
   i=[0, 1, 2, 3]
   
largest = 0 i.e 4

Loop 1:
n = 4
largest = 4

Loop 2:
n = 7
largest = 7

Loop 3:
n = 2
largest = 7

Loop 4:
n = 7
largest = 9

**Final largest = 9**

**Output = 9**
