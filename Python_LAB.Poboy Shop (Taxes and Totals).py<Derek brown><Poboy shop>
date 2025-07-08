#Boudreaux and Thibodeaux have a po-boy shop selling catfish poboys for $14.95, roast beef poboys for $13.95, sausage poboys for $12.95, and a cup of gumbo for $4.95. Sales tax is 9.45%
#You will write a program that does the following:

#prints out to the screen the menu items
#prompts the user for the item the user wishes to order (the user should only be able to order ONE ITEM)
#calculates the user's total due based on the item they've ordered (the subtotal) with sales tax (note: sales tax is a percentage of the subtotal added to the subtotal)
#prints out to the screen the user's total

SALES_TAXES = 9.49

#Menu: items list => price 


menu = {
    "1. catfish poboys": 14.95,
    "2. roast beef poboys": 13.95,
    "3. sausage poboy poboys": 12.95,
    "4. Cup of gumbo": 4.95
    }

print("Welcome to Boudreaux and Thibodeaux")
print(menu)

for item, price in menu.items():
    print(f"- {item.title()} Poboys: ${price:2f}")

total = 0.95

while True:
    choice = input("n\ Enter the what you would like:").lower()
    if choice in menu:
        total += menu[choice]
        print(f"Added {choice.title()}poboy - ${menu[choice]:2f}")
    else: 
        print("Sorry you may only able to order one Items from this list.")
    break

#Calcute sales tax 
tax = total * SALES_TAXES 
grand_total = total + tax

print("n\Order Summary:")
print(f"Subtotal: ${total :2f}")
print(f"tax(9.49): ${tax:.2f}")
print(f"Total:{grand_total:.2f}")
print("Thank you for visting Boudreaux and Thibodeaux ")
