#pangram approach
'''
s=input()
s.lower()
s=set(s)
s1={'x', 'a', 'g', 'p', 'z', 'e', 'b', 'l', 'v', 'm', 'r', 'h', 'y', 'c', 'u', 'k', 'n', 'w', 'i', 'o', 'j', 't', 'q', 'f', 's', 'd'}

if s.issuperset(s1):
    print("pangram")
else:
    print("not pangram")
    '''
#approach 2
'''
s=input()
s.lower()
d={}
s1={'x', 'a', 'g', 'p', 'z', 'e', 'b', 'l', 'v', 'm', 'r', 'h', 'y', 'c', 'u', 'k', 'n', 'w', 'i', 'o', 'j', 't', 'q', 'f', 's', 'd'}
'''
#first repeating character
'''
t=int(input())
while t>0:
    s=input()
    a=tuple(s)
    print(a)
    for i in range(len(a)):
        for j in range(1,len(a)):
            if a[i]==a[j]:
                print(a[j])
                break
        break
    t=t-1
    '''
#phone book
'''
n=int(input())
d={}
for i in range(n):
    t,p=input().split()
    d[t]=p
while True:
    s=input()
    if s in d:
        print(f"{s}={d[s]}")
    else:
        print("Not found")
   '''
'''
#most repeated word
n=int(input())
d={}
for i in range(n):
    s=input()
    if s in d:
        d[s]+=1
    else:
        d[s]=1
#print(d)
x=max(d.values())
#print(x)
l=[]
for i in d:
    if d[i]==x:
        l.append(i)
print(max(l),x)
  '''
#database recovery
'''
t=int(input())
for i in range(1,t+1):
    d={}
    n,r=map(int,input().split())
    while(r>0):
        std,s=map(int,input().split())
        if s not in d:
            d[s]=[std]
        else:
            d[s].append(std)
        r-=1
    for j in d:
        if (len(d[j])>n) and (len(set(d[j]))==len(d[j])):
            print(f"Scenario #{i} : possible")
            break
    else:
        print(f"Scenario #{i} : Impossible")
        '''
#graphs
n=int(input())
route={}
for i in range(n):
    c1,c2=input().split()
    if c1 not in route:
        route[c1]=[c2]
    else:
        route[c1].append(c2)
print(route)
