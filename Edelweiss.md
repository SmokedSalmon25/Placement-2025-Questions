# Edelweiss - Test

## Speed Math
- 60 questions, 15 minutes, random questions like multiply some numbers, find the root of a number, some % of a number

---

## Quant
**50 mins**

- 2 x n array of floats, each column sums to one. Per column, you select 1 number. Each row, you take the sum of the selected numbers. Prove that there exists a selection such that in each row, the sum of the selected numbers is less than (n + 1) / 4
- Prime p, a^p + b^p = c^p + d^p, show that |a - b| + |c - d| >= p
- Given 14 day trading period, what is the length of the smallest guaranteed longest increasing subsequence? What about when the trading period is 100?
- 5 races given, each race has a bunch of horses, with odds (bets placed). If you place k:1 bet, you win k + 1 if horse wins, else you lose. Which races were profitable?
- Pick n + 1 numbers from {1, 2, …, 2n}. At least one pair exists where one divides the other.
- Game 1: Probability of winning ith round is 10^-i  
  Game 2: 1 - 100, if you draw multiple of 9 you win  
  Which is better?

---

## Dev
**25 mins**

- Some crazy order book implementation - needed to implement a burst of orders and print out the remaining order book
- F1 and F2 are two correlated stocks  
  F1 ~ b + aF2  
  How will you find a and b
- How will you update them in real time trading
- Make a trading strategy now
- Some integer overflow bug while multiplying, needed to find bug
- Given code, needed to find why slow. One was that while iterating they used auto, and second was even though operations were read only, they did auto and not auto&
- Some class inheritance with overriding init functions
