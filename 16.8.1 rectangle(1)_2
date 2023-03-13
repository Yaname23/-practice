from rectangle import Rectangle, Square, Circle

#далее создаем два прямоугольника

rect_1 = Rectangle(3,4)
rect_2 = Rectangle(12,5)
#вывод площади наших двух прямоугольников
print("площадь 1 прямоугольника: ", rect_1.get_area())
print("площадь 2 прямоугольника: ", rect_2.get_area())

#далее создаем квадраты
square_1 = Square(5)
square_2 = Square(10)

print("площадь квардата 1: ", square_1.get_area_square())
print("площадь квардата 2: ",  square_2.get_area_square())

#далее создаём круги
circle_1 = Circle(3)
circle_2 = Circle(9)

print("площадь круга 1: ", circle_1.get_area())
print("площадь круга 2: ", circle_2.get_area())


figures = [rect_1,rect_2,square_1,square_2, circle_1, circle_2]

for figure in figures:
    if isinstance(figure, Square):
        print(figure.get_area_square())
    elif isinstance(figure, Circle):
        print(figure.get_area())
    else:
        print(figure.get_area())
