import time
print("Simple Calculator")
def add(num1,num2):
	return num1 + num2
#
def sub(num1,num2):
	return num1 - num2
#
def div(num1,num2):
	return num1 / num2
#
def mul():
	return num1 * num2
def main():
	#Modified/Created By Raym Penamora
	ip1 = input("""What do you want to do?
1.) Use Calculator
2.) Exit
>>""")
	if ip1 == "1":
		def main2():
			print("""Please select operation
1.) Addition
2.) Subtraction
3.) Multiplication
4.) Division""")
			ip2 = input(">>")
			var1 = int(input("Enter first number:"))
			var2 = int(input("Enter second number:"))
			if ip2 == "1":
				print(var1, "+" , var2, "=", add(var1, var2))
				print("")
				print("")
				main()
			elif ip2 == "2":
				print(var1, "-" , var2, "=", sub(var1, var2))
				print("")
				print("")
				main()
			elif ip2 == "3":
				print(var1, "x" , var2, "=", mul(var1, var2))
				print("")
				print("")
				main()
			elif ip2 == "4":
				print(var1, "/" , var2, "=", div(var1, var2))
				print("")
				print("")
				main()
			else:
				print("Syntax Error!")
				print("")
				main()
		main2()
	elif ip1 =="2":
		exit("Goodbye")
		time.sleep(0.2)
	else:
		print("Syntax error!")
		print("Please try again!")
		time.sleep(0.1)
		main()
main()
