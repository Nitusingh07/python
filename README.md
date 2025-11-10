# python
a = int(input("Enter length a: "))
b = int(input("Enter length b: "))
c = int(input("Enter length c: "))

if a + b > c and b + c > a and c + a > b:
    if a == b == c:
        print("It is an equilateral triangle")
    elif a == b or b == c or c == a:
        print("It is an isosceles triangle")
    else:
        print("It is a scalene triangle")
else:
    print("It's not a triangle")
