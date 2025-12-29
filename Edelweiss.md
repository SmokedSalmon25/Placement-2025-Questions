# Edelweiss
# Test

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

# Interview

## Questions

- What day was 9/11

- 3 die of 10 sides, 0, 1, 2, …, 9, probability that the sum is divisible by 10

- Some order book based question, everything was explained, very intuition based

- What is R^2? Can it be negative?

- Positive skew, is mean > median

- Something about half life

- Biased coin, 0.6 head, 0.4 tail, if head you get double the amount you bet, if tail you lose the bet amount, how much should you bet?

- N × n square, fill with 0 and 1, how should you fill so that row and column sum is even. If n × m, what is the constraints on n and m

- 9 integer points in a 3D plane, all 9C2 line segments are drawn, prove at least one line segment contains a point with all integer values

- 2 × n array, each array has a rabbit. Each rabbit can jump to adjacent box (NOT DIAGONAL). They jump such that after jump also each box has exactly one rabbit. They make one jump. How many next states can possibly occur.
