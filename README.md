# Concatenation-in-python
Concatenating means obtaining a new string that contains both of the original strings. In Python, there are a few ways to concatenate or combine strings. The new string that is created is referred to as a string object. In order to merge two strings into a single object, you may use the + operator.


str1=input('str1: ')
str2=input('str2: ')
str3=str1[1::]+str2[1::]
if len(str3)==0:
    print('null')
else:
    print(str3)

str4=input('')
print('str4'*4)
print(str4[::-1]*3)

str5=input()
x=str5[:3]
if len(str5)<=3:
    print (str5)
else:
    print(x*3)

str6=input()
n=int(input())
print(str6*n)


str7=input()
num=int(input())
if num<0:
    print('num should be positive,less than length of str')
else:
    print(num*str7[:num])
