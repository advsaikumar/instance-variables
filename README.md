class Test:
    def __init__(self):
        self.a=10     #Inside Constructor by using self variable

    def m1(self):
        self.b=20     #Inside Instance Method by using self variable       

t=Test()
t.m1()
t.c=30               #Outside of the class by using object reference variable
print(t.__dict__)
