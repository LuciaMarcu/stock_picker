# Project: Stock picker

Part of The Odin Project Ruby fundamentals.

I had to implement a method #stock_picker that takes in an array of stock prices, one for each hypothetical day. 
It should return a pair of days representing the best day to buy and the best day to sell. Days start at 0.

Quick Tips:
You need to buy before you can sell.
Pay attention to edge cases like when the lowest day is the last day or the highest day is the first day.
> stock_picker([17,3,6,9,15,8,6,1,10])
  => [1,4]  # for a profit of $15 - $3 == $12
  
  Try it here: https://replit.com/@LuciaMarcu/Stock-picker#main.rb
