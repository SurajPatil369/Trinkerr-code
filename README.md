# Trinkerr-code
Sorting the Characters


```
def sortString(strs):
    strs=list(strs)
    n=len(strs)
    low=0
    high=n-1
    while(low<high):
        if (strs[low]=='a'):
            low+=1
        if(strs[high]=='c'):
            high-=1
        elif(strs[low]=='c' and strs[high]=='a'):
            strs[low],strs[high]=strs[high],strs[low]
            
    strs=''.join(strs)
    print(strs)

sortString('accacca')
```
