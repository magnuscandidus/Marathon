# Marathon
# cook your dish here
t=int(input())
while t:
    d1,d2,a,b,c=map(int,input().split())
    x=d1*d2
    if(10<=x<21):
        print(a)
    elif(21<=x<42):
        print(b)
    elif(42<=x):
        print(c)
    else:
        print("0")
    t-=1
