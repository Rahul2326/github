# github
python codes
class vehicle:
    def __init__(self,mileage,cost):
        self.mileage=mileage
        self.cost=cost
    def show_details(self):
        print("i am a vehicle")
        print("the mileage is ", self.mileage)
        print("the cost is ", self.cost)

v1=vehicle(300,1000)
v1.show_details()
        
        
class car(vehicle):
    def __init__(self,mileage,cost,tyres,hp):
        super().__init__(mileage,cost)
        self.tyres=tyres
        self.hp=hp
    def show_car(self):
        print("i am a car")
        print("number of tyres are " , self.tyres)
        print("value of horsepower is ", self.hp)

c1=car(200,1200,4,300)
c1.show_details()
c1.show_car()
