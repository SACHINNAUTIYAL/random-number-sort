
import numpy as np

lists=[]

for i in range(0,10):

    x=np.random.randint(-1,500)

    lists.append(x)

print (lists)

sorted_list=sorted(lists)

print(sorted_list)

