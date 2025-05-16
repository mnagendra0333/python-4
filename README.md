#program to revverse a 4digit number. i/p=4562 o/p=2654
num= int(input("enter the number:"))
rev=0
while num>0: # num!=0:
    d= num%10
    rev=rev*10+d
    num//=10
print(rev)
