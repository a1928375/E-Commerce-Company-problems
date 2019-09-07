# E-Commerce-Company-problems

1. 
    (1) You've been given a list of historical stock prices for a single day for Amazon stock. The index of the list represents the             timestamp, so the element at index of 0 is the initial price of the stock, the element at index 1 is the next recorded price of the         stock for that day, etc. Your task is to write a function that will return the maximum profit possible from the purchase and sale of a     single share of Amazon stock on that day. Keep in mind to try to make this as efficient as possible.

    (2) For example, if you were given the list of stock prices:     prices = [12,11,15,3,10]
    Then your function would return the maximum possible profit, which would be 7 (buying at 3 and selling at 10).

    (3) Requirements
    Try to solve this problem with paper/pencil first without using an IDE. Also keep in mind you should be able to come up with a better       solution than just brute forcing every possible sale combination. Also you can't "short" a stock, you must buy before you sell the         stock.
    
2. 
    (1) Given a list of integers, write a function that will return a list, in which for each index the element will be the product of all     the integers except for the element at that index

    (2) For example, an input of [1,2,3,4] would return [24,12,8,6] by performing [2×3×4,1×3×4,1×2×4,1×2×3]
    
3. 
    (1) Given two rectangles, determine if they overlap. The rectangles are defined as a Dictionary, for example:

     r1 = {# x and y coordinates of the bottom-left corner of the rectangle
         'x': 2 , 'y': 4,
          # Width and Height of rectangle
          'w':5,'h':12}

     (2) If the rectangles do overlap, return the dictionary which describes the overlapping section

     (3) Requirements
     Make sure the dictionary you output is in the same form as the input.
