import numpy as np
# initialize array for prices
prices = np.array([[40, 35, 20], [21, 48, 70]])
# Code starts here
prices = prices.flatten()
# flatten the array
print(prices)

# minimum price
buying_price = prices.min()
print(buying_price)

index = list(prices)
print(index)
index = index.index(buying_price)
print(index)
for i in range(index, len(prices)):
    selling_price =  prices.max()
print(selling_price)
profit = selling_price - buying_price
print(profit)    
# index of buying price


# create subset


# selling price


# profit

# display


# Code ends here
