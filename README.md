# print all positive numbers in a list
n=int(input("length of list:"))
list1=[]
for i in range (n):
    element=int(input("enter the element:"))
    list1.append(element)
print("list elements are:",list1)
for num in list1:
    if num>=0:
        print(num ,end=",")
