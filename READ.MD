num_lemonades_sold= 30
num_hours_worked=10

lemons_per_lemonade=4
lemon_cost=0.5
lemonade_cost=5

print()
print()

revenue= num_lemonades_sold+lemonade_cost
print('Revenue:', revenue)

expenses= num_lemonades_sold* lemons_per_lemonade*lemon_cost
print('Expenses:', expenses)

profit= revenue-expenses
print(profit)

pay_per_hour= profit/num_hours_worked
print(pay_per_hour)
print("You made ${}, or ${} per hour.".format(profit, profit/ num_hours_worked))
