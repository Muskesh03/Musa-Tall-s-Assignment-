# Musa-Talle-s-Assignment-
# Filename: number_classifier.py

def is_even(number):
    return number % 2 == 0

def main():
    try:
        user_input = int(input("Enter a number: "))
        
        if user_input == 0:
            print("The entered number is zero.")
        elif is_even(user_input):
            print("The entered number is even.")
        else:
            print("The entered number is odd.")
    
    except ValueError:
        print("Invalid input. Please enter a valid number.")

if __name__ == "__main__":
    main()
