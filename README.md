# Toyota Pricing Analysis - Pricing Analyst Project
# Author: Statistics Graduate, Kampala

# Function to calculate profit
def calculate_profit(selling_price, cost_price):
    profit = selling_price - cost_price
    print(profit)

# Test profit for 3 cars
calculate_profit(25000,20000)  # Prado
calculate_profit(22000,18000)  # Hilux
calculate_profit(15000,12000)  # Corolla

# Dictionary of car models and profits
car_profit_dict = {
    'prado2020': 5000,
    'hilux2021': 4000,
    'corolla2019': 3000
}

# Loop to show each car profit
for key, value in car_profit_dict.items():
    print(key, '->', value)

# Check if profit is Good or Low
for profit in car_profit_dict.values():
    if profit > 4000:
        print('Good')
    else:
        print('Low')
