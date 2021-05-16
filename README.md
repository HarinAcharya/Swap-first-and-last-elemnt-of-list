# Swap-first-and-last-elemnt-of-list

def swapList(newList):
    newList[0],newList[-1]=newList[-1],newList[0]
    return newList

newList=[1,2,3,4,5]
print(swapList(newList))
