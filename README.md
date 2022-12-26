# 9.sum-of-n-febinocci-series
n=int(input('Enter any number:'))
a=0
b=1
c=0
sum=0
while(n!=0):
    print(a)
    sum=sum+a
    t=a+b
    a=b
    b=t
    n=n-1
print('Sum is',sum)
    
