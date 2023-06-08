def add(num1, num2):
    return num1 + num2

def subtract(num1, num2):
    return num1 - num2

def(num1, num2):
    return num1 * num2

def divide(num1, num2):
    if num2 == 0:
        return "错误：除数不能为0"
    else:
        return num1 / num2

print("欢迎使用计算器程序！")
print("请选择要进行的操作：")
print("1. 加法")
print("2. 减法")
print("3. 乘法")
print("4. 除法")

operation = input("请输入操作编号：")

num1 = float(input("请输入第一个数字："))
num2 =(input("请输入第二个数字："))

if operation == "1":
    result = add(num1, num2)
    print("计算结果：", result)
elif operation == "2":
    result = subtract(num1, num2)
    print("计算结果：", result)
elif operation == "3":
    result = multiply(num1, num2)
    print("计算结果：", result)
elif operation == "4":
    result = divide(num1, num2)
    print("计算结果：", result)
else:
    print("错误：无效的操作编号")
