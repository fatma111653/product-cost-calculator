# product-cost-calculator
#This program takes the name, price, and quantity of a product,
# then calculates and prints the total cost for that product.

name = input("Enter the name of a product: ")
price = float(input("Enter the price of the product: "))
quantity = int(input("Enter the quantity of the product: "))

product_info = {
    "name": name,
    "price": price,
    "quantity": quantity,
    "total_cost": price * quantity
}

print(f"Total cost for {product_info['name']} is {product_info['total_cost']}")
