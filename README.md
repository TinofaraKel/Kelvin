# Kelvin
School
n=int(input("enter the number of students  height to be inserted:"))
a=[]
for i in range(0,n):
    elem=int(input("enter height:"))
    a.append(elem)
avg=sum(a)/n
print("average height is equal to",round(avg,2))
