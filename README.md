def cubic(a,b,c,d):
    u = (-b ** 3 / ((27 * a) ** 3)) + ((b * c) / (6 * a) ** 2) - (d / (2 * a))
    t = ((c / (3 * a)) - ((b ** 2) / ((9 * a) ** 2))) ** 3 - (b / (3 * a))
    x = (u - (((u ** 2) + (t ** 3)) ** 0.5) ** (1 / 3))
    return x



a=float(input("what is a: "))
b=float(input("what is b: "))
c=float(input("what is c: "))
d=float(input("what is d: "))

print("the root of the cubic is" ,cubic(a,b,c,d))




