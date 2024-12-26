# Project-6
#  Program 6: WAP to swap the first n characters of two strings.
code= str1 = input("enter first string: ")
str2 = input("enter second string: ")
n1 = int(input("enter no of character which is to be swap:"))
n = str1[ :n1]
m = str2[ :n1]
if n1 <= min(len(str1),len(str2)):
print(str1.replace(n,m))
else:
print(str2.replace(m,n))
![Screenshot_20241227-010154_Moto App Launcher](https://github.com/user-attachments/assets/9e8e0efc-88c8-4b01-89d5-2831540e5248)
