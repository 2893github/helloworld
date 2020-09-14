#to find divisors list

num = int(input("Please choose a number to divide: "))

list = range(1,num+1)

divisorList = []

for i in list:
    if num%i == 0:
        divisorList.append(i)

print(divisorList)
