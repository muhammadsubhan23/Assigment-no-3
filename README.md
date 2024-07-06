# Assigment-no-3
marks =int(input("ENTER YOUR MARKS"))
rollnumber = int(input("ENTER YOUR ROLL NUMBER"))
grade = ""

if(marks >=90 ):
    grade = "your Grade is A1" 
    
elif(marks >=80):
    grade = "Your Grade is A"
    
elif(marks >=80):
    grade = "Your Grade is b"
    
elif(marks >=80):
    grade = "Your Grade is c"
    
elif(marks >=80):
    grade = "Your Grade is d"
    
else:
    "your are  fail"

print("rollnumber:",rollnumber)
print("marks:",marks)
print("grade:",grade)

# convert tempereture program


def celsius_to_fahrenheit(celsius):
    fahrenheit = (celsius * 9/5) + 32
    return fahrenheit

def fahrenheit_to_celsius(fahrenheit):
    celsius = (fahrenheit - 32) * 5/9
    return celsius


if __name__ == "__main__":
    print("Temperature Converter between Celsius and Fahrenheit")
    print("============================")
    print("1. Celsius to Fahrenheit")
    print("2. Fahrenheit to Celsius")
    print("============================")
    choice = int(input("Enter your choice (1 or 2): "))

    if choice == 1:
        celsius = float(input("Enter temperature in Celsius: "))
        fahrenheit = celsius_to_fahrenheit(celsius)
        print(f"{celsius} Celsius = {fahrenheit} Fahrenheit")

    elif choice == 2:
        fahrenheit = float(input("Enter temperature in Fahrenheit: "))
        celsius = fahrenheit_to_celsius(fahrenheit)
        print(f"{fahrenheit} Fahrenheit = {celsius} Celsius")

    else:
        print("Invalid choice. Please enter either 1 or 2.")


# scalene Program
