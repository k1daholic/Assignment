# Function to calculate discount
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        discounted_price = price - (price * discount_percent / 100)
        return discounted_price
    else:
        return price

# Prompt the user for inputs
price = float(input("Enter the original price: "))
discount_percent = float(input("Enter the discount percentage: "))

# Get the final price
final_price = calculate_discount(price, discount_percent)

# Print the result
print("Final price:", final_price)
