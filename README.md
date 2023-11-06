# Analog-electronic-
vCC=int(input("enter the value of vCC:"))
vBE=float(input("enter the value of vBE:"))
RE=int(input("enter the value of RE:"))
beta=int(input("enter the value of beta:"))
RB=int(input("enter the value of RB:"))
RC=float(input("enter the value of RC:"))
IB=(vCC-vBE)/(RB+(beta+1)*RE)
IC=beta*IB
print("the value of base current",IB)
print("the value of collector current",IC)
