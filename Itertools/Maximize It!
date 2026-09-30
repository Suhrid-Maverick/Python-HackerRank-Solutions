from itertools import product
n,m=input().split()
y=int(m)
l=[]

for i in range(int(n)):
    x=list(map(int,input().split()))[1:]
    l.append(x)

s=map(lambda x:sum(i*i for i in x)%y,product(*l))
print(max(s))
