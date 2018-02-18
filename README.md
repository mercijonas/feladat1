# feladat1
a=6
b=4
a=a+b
b=a-b
a=a-b
print(a,b)

# feladat3
def feladat_3(x):
    if x>-2 and x<0:
        return 2*x
    elif x>=0 and x<2:
        return x*x
    elif x>2:
        return 10
    else:
        return("A függvény nincs értelmezve")


def main():
    print(feladat_3(2))

if __name__=='__main__':
    main()
    
# feladat5
def feladat_5(a,b,c,d):
    if d>=0:
        return(a,c,b,d)
    else:
        return(a,b,d,c)
def main():
    print(feladat_5(2,3,4,5))
if __name__=='__main__':
    main()
