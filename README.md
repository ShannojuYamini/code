DAY 1
1)SUM OF DIGITS
s=input()
sum=0
for i in range(0,len(s)):
    if s[i].isdigit():
        sum+=int(s[i])
print(sum) 
2)COUNT OF DIGITS
s=input()
count=0
for i in range(0,len(s)):
    if s[i].isdigit():
        count+=1
print(count) 
3)PALINDROME
s='malayalam'
s1=''
for i in range(len(s)-1,-1,-1):
    s1+=s[i]
if(s1==s):
    print('palindrome')
else:
    print('not')
4)VOWELS
S='yamini'
vowels=['a','e','i','o','u']
count=0
for c in S:
    if c in vowels:
        count+=1
print(count)
5)MEMBERSHIP 
s='123ABC$'
count=0
for i in s:
    if (not(i.isdigit())):
        count+=1
print(count)
6)even or odd using function
def num(n):
    if n%2==0:
        return"even"
    else:
        return"odd"
print(num(13)) 
7)even or odd without using modulus
def num(n):
    if 1&n==0:
        return"even"
    else:
        return"odd"
print(num(13))
8)ARRAY
def check(arr):
    count=0
    for i in arr:
        if i%4==0 and i%6==0:
            count+=1
    return count
arr=[1,36,24,9,2,12]
print(check(arr))
9)REVERSE A STRING
def check(s):
    rev=''
    for i in s:
        rev=i+rev
    return rev
s='sri devi is engineering college'   
print(check(s))  
10)def check(s):
    s=s.split()
    s=list(reversed(s)) # s became reverse string
    print(s)
    for i in s:
        rev=i[::-1] #characters of reverse list
        print(rev,end=' ')
s='sri devi is engineering college'   
check(s)    
    
output:['college', 'engineering', 'is', 'devi', 'sri']
egelloc gnireenigne si ived irs 

