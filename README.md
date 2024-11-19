# python-control-flows
def large_power(base, exponent):
    """
    Check if base raised to the power of exponent is greater than 5000.
    """
    # Calculate the result
    result = base ** exponent

    # Check and return the result
    if result > 5000:
        return True
    else:
        return False

def divisible_by_ten(num):
    """
    Check if the number is divisible by 10.
    """
    # Check divisibility using modulo
    if num % 10 == 0:
        return True
    else:
        return False

# Main program
if __name__ == "__main__":
    # Test large_power
    base = int(input("Enter the base for large_power: "))
    exponent = int(input("Enter the exponent for large_power: "))
    print(f"Is {base}^{exponent} greater than 5000? {large_power(base, exponent)}")

    # Test divisible_by_ten
    num = int(input("\nEnter a number to check divisibility by 10: "))
    print(f"Is {num} divisible by 10? {divisible_by_ten(num)}")
