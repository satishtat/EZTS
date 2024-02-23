#p1 #even odd index
'''
d=input()
ev=""
for i in range(len(d)):
    if i%2==1:
        print(d[i],end="")
    else:
        ev+=d[i]
print(ev)
'''
#p1 approach 2
'''
s=input()
es=s[::2]
os=s[1::2]
print(os+es)
'''
#p2 approach1 # occurance of a character
'''
s=input()
ch=input()
count=0
for i in s:
    if ch==i:
        count+=1
print(count)
'''
#p2 approach 2
'''
s=input()
ch=input()
print(s.count(ch))
'''
#p3 #occurance of character at even index
'''
s=input()
ch=input()
c=0
for i in range(len(s)):
    if i%2==0 and s[i]==ch:
        c+=1
print(c)
'''
#p4 vowels in a string
'''
s=input()
s.lower()
c=0
d=0
for i in s:
    if i=='a' or i=='e' or i=='i' or i=='o' or i=='u':
        c=c+1
    else:
        d+=1
if d>0:
    print("No")
else:
    print("Yes")
    '''
#p4 approach 2
'''
s=input()
v="aeiouAEIOU"
c=0
for i in s:
    if i in v:
        c+=1
if c==len(s):
    print("Yes")
else:
    print("No")
    '''
#p5 digits in string
'''
s=input()
c=0
d="0123456789"
for i in s:
    if i not in d:
        c+=1
if c>0:
    print("No")
else:
    print("Yes")
'''
#approach 2
'''
s=input()
c=0
d="1234567890"
for i in s:
    if i in d:
        c+=1
if c==len(s):
    print("Yes")
else:
    print("No")
    '''
#approach 3
'''
s=input()
c=0
d="1234567890"
if s.isdigit() ==True:
    print("Yes")
else:
    print("No")
    '''
#p6 print count of vowels and consonents
'''
s=input()
s.lower()
o="aeiou"
c=0
d=0
for i in s:
    if i.isalpha() and i in o:
        c=c+1
    else:
        d+=1
print(c,d)
'''
#p7 #not worked
'''
s=input()
c=0
d=""
for i in s:
    if i not in d:
        d+=i
for j in d:
    print(f"{j}{s.count(j)}",end="")
'''
#approach 1 # counting character sequence linearly
'''
s=input()
c=1
r=""
for i in range(1,len(s)):
    if s[i]==s[i-1]:
        c=c+1
    else:
        r=r+s[i-1]
        r=r+str(c)
        c=1
r=r+s[len(s)-1]+str(c)
print(r)
#input #aabbcc #output #a2b2c2
'''
#p8 #printing count of words , vowels, consonents
'''
t=int(input())
for i in range (t):
    s=list(input().split())
    v="aeiouAEIOU"
    o=0
    c=0
    w=len(s)
    for j in s:
        for k in j:
            if k.isalpha():
                if k in v:
                    o=o+1
                else:
                    c+=1
    print(w,o,c)
    '''
#approach 2
'''
t=int(input())
for i in range (t):
    s=input()
    v="aeiouAEIOU"
    o=0
    c=0
    for j in s:
            if j.isalpha():
                if j in v:
                    o=o+1
                else:
                    c+=1
    w=len(s.split())
    print(w,o,c)
            '''
#p9 #difference
'''
t=int(input())
for i in range(t):
    a,b=input().split()
    r=""
    for i in b:
        if i not in a:
            r=r+i
    print(r)
'''
#approach 2
'''
a,b=input().split()
for i in a:
    if i in b:
        b=b.replace(i,'')
print(b)
'''
#p10 printing character after updation
'''
t=int(input())
for i in range (t):
    a,b=input().split()
    b=int(b)
    r=""
    for i in a:
        k=ord(i)+b
        if k>122:
            k=96+(k-122)
            r=r+chr(k)
        else:
            r=r+chr(k)
    print(r)
    '''
#oops  #p11
'''
class srinu:
    a=2
    b=22
    def junnu(self):
        print("extrodinary")
class seenu:
    def junnu(self):            #self method is used to allocate function to its proposed class
        print("stunning")
ob=srinu()
ob2=seenu()
print(ob.a)
print(ob.b)
ob.junnu()
ob2.junnu()
'''
#p12
'''
class classa:
    def factorial(self,n):
        r=1
        for i in range(1,n+1):
            r=r*i
        print(r)
obj=classa()
obj.factorial(5)
        '''
#p13
'''
class claaaas:
    r=1
    def __init__(self,n):
        self.n=n
        print(n)
    def fact(self):
        r=1
        n=self.n
        if n>0:
            r=r*n
            n=self.n-1
            self.fact()
        else:
            print(r)
ob=claaaas(5)
ob.fact()
   '''     
        
