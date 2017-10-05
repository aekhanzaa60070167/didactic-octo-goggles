def cal(num1,num2):
    summ = summation(num1,num2)
    subb = subbtraction(num1,num2)
    return subb, summ

def summation(n1, n2):
	return n1 + n2

def subbtraction(n1, n2):
	return n1 - n2

def test1():
	print("เอกหล่อมากกกกกกกกกกกกกกก")
cal(int(input()), int(input()))