## python
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



 ## to chech whether its leap year or not 
year=int(input("year:"))
if year%4==0:
        if year%100==0:
              if year%400==0:
                   print("leap year")
              else :print("not leap year")
        else: print("leap year")
else:
    print("not leap year") 
    
