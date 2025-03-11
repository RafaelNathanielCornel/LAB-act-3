def check_number(num):
    while True:
        a = int(input("type any number:"))
        if a % 2 == 0:
            print(a, ' is an even number')
        else:
            print(a, "is an odd number")

check_number(1)
