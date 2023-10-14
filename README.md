# tsy.xnjnj.io
df
![1ff02e3ba9cecf53fa276611f21c6881](https://github.com/Mishanaytsy/tsy.xnjnj.io/assets/145833260/0f14d44e-f4a8-4748-8928-7d2e36cf61f7)

[Ufrom turtle import *
from itertools import product

def f2 ():

    print('x y z w')
    for x in range(2):
        for y in range(2):
            for z in range(2):
                for w in range(2):
                    if (not(y<=x) or (z<=w) or not(z))==False:
                        print(x, y, z, w)
def f5 ():

    for i in range(1,100):
        num=(bin(i)[2:])
        if num.count('1')%2==0:
            chislo='10'+num[2:]+'0'

        if num.count('1')%2!=0:
            chislo='11'+num[2:]+'1'
        if int(chislo,2)>40:
            print (i, int(chislo,2))
            break
def f6 ():
        
    left(90)
    for i in range(7):
        forward(300)
        right(120)
    pu()
    for x in range(1,9):
        for y in range(1,10):
            goto(x*30,y*30)
            dot(2)
    done()

def f8 ():

    k=0
    n='16 36 56 76 61 63 65 67'
    nn=n.split()
    nums=product('01234567',repeat=5)
    for n in nums:
        numb=''.join(n)
        if numb.count('6')==1 and numb[0]!='0':
            if all(not(x in numb) for x in nn):
                k+=1
    print(k)
    
def f12():

    for n in range(4, 10000):
        s = '5' + n*'2'
        while '52' in s or '2222' in s or '1122' in s:
            s = s.replace('52', '11', 1)
            s = s.replace('2222', '5', 1)
            s = s.replace('1122', '25', 1)
        if sum(map(int, s)) == 64:
            print(n)





ploading tabl.py…]()






| № | что-то |
| ------ | ------ |
|1| р |
|2| c\р |
|3| p (exel) |
|4| p |
|5| c |
|6| c |
|7| p |
|8| c |
|9| exel |
|10| p |
|11| p |
|12| c |
|13| p |
|14| p\c |
|15| с |
|16| с |
|17|  |
|18|  |
|19|  |
|20|  |
|21|  |
|22|  |
|23|  |
|24|  |
|25|  |
|26|  |
|27|  |
