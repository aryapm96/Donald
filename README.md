from array import *

def create(n):
    arr=array('i',[])
    for i in range(n):
        x=int(input("Enter the elements:"))
        arr.append(x)
    print(arr)
    p=int(input("Enter the number to search:"))
    
    return result(arr,p)
    
def result(arr,p):
    k=0
    for s in arr:
        if s==p:
            break
        k+=1
    print(arr.index(p))
    
    
n=int(input("Enter the length of array:"))

create(n)
