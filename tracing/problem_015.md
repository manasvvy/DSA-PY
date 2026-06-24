**problem**
nums = [8, 3, 6, 2]

smallest = nums[0]

for n in nums:
    if n < smallest:
        smallest = n

print(smallest)

**my trace**
Loop 1:
n = 8
smallest = 8<8 = False = 8

Loop 2:
n = 3
smallest = 3<8 = True = 3

Loop 3:
n = 3<6 = True = 3
smallest = 3

Loop 4:
n = 2
smallest = 2<3= True = 2

Final smallest = 2

Output = 2
