**problem**

nums = [4, 1, 6, 2]

count = 0

for n in nums:
    if n > 3:
        count = count + 1

print(count)

**my trace**
Loop 1:
n = 4
4>3 True
count = 0+1=1

Loop 2:
n = 1 
1>3 False
count = 1

Loop 3:
n = 6
6>3 True
count = 1+1=2

Loop 4:
n = 2
2>3  False
count = 2

**Final count =2** 

**Output = 2**
