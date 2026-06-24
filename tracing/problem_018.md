**problem**
nums = [1, 4, 5, 8, 7]

odd_count = 0

for n in nums:
    if n % 2 != 0:
        odd_count = odd_count + 1

print(odd_count)

**my trace**

Loop 1:
n = 1
odd_count = 0+1=1

Loop 2:
n = 4
odd_count = 1

Loop 3:
n = 5
odd_count = 1+1=2

Loop 4:
n = 8
odd_count = 2

Loop 5:
n = 7
odd_count = 2+1=3

**Final odd_count = 3**

**Output = 3**
