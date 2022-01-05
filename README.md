# Exercise-2
#length
length = [30, 40, 50]
num1 = length[0]
num2 = length[1]
num3 = length[2]
#Breadth
b = 20
# height
h = 15
# volume of cuboid
def volume_of_Cuboid( num1 , h , b ):
    return (num1 * h * b)
def volume_of_Cuboid( num2 , h , b ):
    return (num2 * h * b)
def volume_of_Cuboid( num3 , h , b ):
    return (num3 * h * b)
    

# Biggest face surface area of cuboid
def Biggest_Surface_Area(num1, b, h):
    if b >= h:
        return num1*b
    else:
        return num1*h
def Biggest_Surface_Area(num2, b, h):
    if b >= h:
        return num2*b
    else:
        return num2*h
def Biggest_Surface_Area(num3, b, h):
    if b >= h:
        return num3*b
    else:
        return num3*h
     
print("When L=30  Volume in cm^3 :" , volume_of_Cuboid(num1, h, b))
print("When L=30 Biggest Surface Area in cm^2 =", Biggest_Surface_Area(num1, h, b))
print("When L=40 Volume in cm^3 :" , volume_of_Cuboid(num2, h, b))
print("When L=40 Biggest Surface Area in cm^2 =", Biggest_Surface_Area(num2, h, b))
print("When L=50 Volume in cm^3 :" , volume_of_Cuboid(num3, h, b))
print("When L=50 Biggest Surface Area in cm^2 =", Biggest_Surface_Area(num3, h, b))
