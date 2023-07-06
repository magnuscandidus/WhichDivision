# WhichDivision
# cook your dish here
t=int(input())
while t:
    r=int(input())
    if(2000<=r):
        print("1")
    elif(1600<=r<2000):
        print("2")
    elif(r<1600):
        print("3")
    else:
        print("0")
    t-=1
