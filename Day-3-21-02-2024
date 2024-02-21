#list methods
'''
.append()
.extend()
.insert()
.remove()
.pop()
.clear()
.sort()
.index()
.copy()
'''
#inbuilt functions
'''
any()
sorted()
len()
all()
'''
#operations
'''
concatination of list(*)
repatation
membership
slicing
'''
#nested list
'''
l=list(list(map(int,input().split())))
print(l)
'''
'''k=list(map(int,input().split()))
for i in range(len(k)):
    count=k.count(i)
    if count>=2:
        print(i)'''
#finding duplicate in a list
'''
n=int(input())
k = list(map(int, input().split()))[:n]
for i in k:
    count = k.count(i)
    if count > 1:
        print(i)
        break
        '''
#approach 2
'''
n=int(input())
a=list(map(int,input().split()))[:n]
a.sort()
for i in range(n-1):
    if a[i]==a[i+1]:
        print(a[i])
        break
'''
#unique elements in an array
'''
n=int(input())
k = list(map(int, input().split()))[:n]
l=[]
for i in k:
    count = k.count(i)
    if count == 1:
        l.append(i)
for l in l:
    print(l,end=" ")
    '''

#approach 2
'''
n=int(input())
k = list(map(int, input().split()))[:n]
l=[]
for i in k:
    count = k.count(i)
    if count == 1:
        print(i,end=" ")
        '''
#gravity flip
'''
sort
'''
#accessing tuple
'''
t=(1,)
methods
.index()
.count()

#deleting
del t
#tuple methods
concatination
repetation
#built in functions
sum()
min()
max()
all()
any()
len()
'''
#approach 1
'''
t=int(input())
for x in range (t):
    n=int(input())
    k=0   #we can use lists instead
    j=0
    for i in range(1,n+1):
        if n%i==0:
            if i%2==0:
                k=k+1
            else:
                j=j+1

if k==j:
    print(1)
else:
    print(0)
    '''
#approach 2
'''
t=int(input())
def fun(t):
    n=int(input())
    res(n,0,0)
    fun(t-1)
def res(n,i,j):
    if n%i==0:
    '''
#pp
'''
t=int(input())
for i in range (t):
    n,x=map(int,input().split())  #items,minfressness
    a=list(map(int,input().split())) #freshness values
    b=list(map(int,input().split()))  #cost of each item
    cost=0
    for i in range(n):
        if a[i]>=x:
            cost=cost+b[i]
            
    print(cost)
    '''
#prime
'''
n=int(input())
count=0
for i in range(1,n+1):
    if n%i==0:
        count=count+1
if count==2:
    print("prime")
else:
    print(" not a prime")
    '''
#perfect number
n=int(input())
s=0
for i in range (2,n+1,2):
    for j in range(1,i):
        if i%j==0:
            s+=j
    if s==i:
        print(i)
    s=0
