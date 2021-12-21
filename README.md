# OOPS-practice
class economic:
    def __init__(self,sales,consumption,price):
        self.sales=sales
        self.consumption=consumption
        self.price=price
        self.output_value=self.price*(self.sales-self.consumption)
        print("The output value is {}".format(self.output_value))
    def NFI(self,input_cost):
        nfi=self.output_value-input_cost
        print("The net farm income is {}".format(nfi))
    def NCI(self,vcc):
        nci=(self.price*self.sales)-vcc
        print("The net cash income {}".format(nci))
