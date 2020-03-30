import random
from queue import *

    
a=[int(),int(),int(),int(),int()]
for var in a:
    var=random.randint(0,10)
b=[int(),int(),int(),int(),int()]
for var in b:
    var=random.randint(0,10)
c=[int(),int(),int(),int(),int()]
for var in c:
    var=random.randint(0,10)
d=[int(),int(),int(),int(),int()]
for var in d:
    var=random.randint(0,10)
e=[int(),int(),int(),int(),int()]
for var in e:
    var=random.randint(0,10)

graphe=[a,b,c,d,e] 
dijkstra(graphe,a[0],e[3])
 
