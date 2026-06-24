**problem**
nums = [3, 8, 2, 10, 5]

largest_even = 0

for n in nums:
    if n % 2 == 0 and n > largest_even:
        largest_even = n

print(largest_even)

**my trace**
Loop 1:
n = 3 Odd so false
largest_even = 0

Loop 2:
n = 8
8>0 True
largest_even = 8

Loop 3:
n = 2
2>8 False
largest_even = 8

Loop 4:
n = 10
10>8 True 
largest_even = 10

Loop 5:
n = 5 odd false
largest_even = 10

**Final largest_even = 10**

**Output = 10**
