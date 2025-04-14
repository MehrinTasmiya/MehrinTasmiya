class SquareCalculator:
    def __init__(self, number1, number2):
        self.number1 = number1
        self.number2 = number2

    def calculate_squares(self):
        square1 = self.number1 ** 2
        square2 = self.number2 ** 2
        return square1, square2

# Example usage
if __name__ == "__main__":
    # Input two numbers
    num1 = int(input("Enter the first number: "))
    num2 = int(input("Enter the second number: "))

    # Create an instance of SquareCalculator
    calculator = SquareCalculator(num1, num2)

    # Calculate and display the squares
    square1, square2 = calculator.calculate_squares()
    print(f"The square of {num1} is {square1}")
    print(f"The square of {num2} is {square2}")
