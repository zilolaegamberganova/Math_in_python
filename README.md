# Math_in_python
This is the mathematic project
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Nolga bo'lish mumkin emas!"

print("Matematika operatsiyalari:")
print("1. Yig'ish")
print("2. Ayirish")
print("3. Ko'paytirish")
print("4. Bo'lish")

# Foydalanuvchidan operatsiyani tanlashni so'rash
choice = input("Tanlovingizni kiriting (1/2/3/4): ")

# Foydalanuvchidan sonlarni kiritishni so'rash
num1 = float(input("Birinchi sonni kiriting: "))
num2 = float(input("Ikkinchi sonni kiriting: "))

# Tanlangan operatsiyani bajarish
if choice == '1':
    print(f"{num1} + {num2} = {add(num1, num2)}")
elif choice == '2':
    print(f"{num1} - {num2} = {subtract(num1, num2)}")
elif choice == '3':
    print(f"{num1} * {num2} = {multiply(num1, num2)}")
elif choice == '4':
    print(f"{num1} / {num2} = {divide(num1, num2)}")
else:
    print("Noto'g'ri tanlov!")
