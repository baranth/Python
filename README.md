r=int(input("enter the value  "))
def Fact(r):
    f=1
    i=1
    for i in range(1,r+1,1):
        f=f*i
    return f
t=Fact(r)
print(t)

