def calculator():
    print("Simple Calculator")
    print("1.Add  2.Sub  3.Mul  4.Div")

    op = int(input("Choose: "))
    a = float(input("Enter A: "))
    b = float(input("Enter B: "))

    if op == 1:
        print("Result:", a + b)
    elif op == 2:
        print("Result:", a - b)
    elif op == 3:
        print("Result:", a * b)
    elif op == 4:
        print("Result:", a / b)
    else:
        print("Invalid choice")

calculator()
