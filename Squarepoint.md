# Square Point

Squarepoint repeats questions from other IITs. Make sure to ask students from other IITs.

---

## Test Questions

---

## SDE

### Aggressive Cows
https://www.geeksforgeeks.org/problems/aggressive-cows/1

---

### Perfect Pair
https://leetcode.com/problems/number-of-perfect-pairs/description/

---

### XOR Product Maximization
Given 3 numbers **A**, **B**, **N**, choose a number **X** between `1` to `2^N` such that the product  
`(A ^ X) * (B ^ X)` is maximized. Return that product.

---

### Strong Team Subarray (O(N))
We are given two teams **A** and **B** that have an equal number of players. Each player has a skill level.

We are allowed to construct another team using players from each team, but it must be a **subarray** consisting of elements from arrays **A** and **B**.

A constructed team is considered a strong team if the skill level is in **non-decreasing order**.

We must return the **maximum sized subarray**.

**Example:**

Team A = {5, 6, 2, 1}
Team B = {3, 2, 1, 2}

From index 2 if we take 2 from team B, then at index 3 we take 2 from Team A, and index 4 2 from team B we get the maximum sized subarray {2,2,2}. The constraints are such that we need to find O(N) soln.

### Expression Evaluation
Given a string with brackets, numbers, spaces, `'+'` and `'-'`. Evaluate the output.

**Example:**

Input: "4 + 5 - (2 + 3)"
Output: 4


The size of the input string was not specified; it was given as a **stream of characters**.  
(Needed to use `getline` or `stringstream` to accept input.)

This question was **common for all**.

---

## Python Paper

### Logs and Pods
A question on logs and pods. Characteristics of logs were given and pods had to be changed accordingly.

Example:  
If logs were of the form `(2, 1, x)`, all pods of a certain type had to be changed.

---

### SquarePoint Permission Manager
An **OOPS** question where you had to write a bunch of functionalities for each of the tasks given.

---

## DQA

### ATM Queue Problem
In a queue, people `1` to `N` are standing in ascending order at an ATM. Each wants to withdraw a certain amount of cash (given in an array), but the maximum cash that the ATM can give at once is `k`.

If they are not able to get the required amount, they go to the back of the queue.

Return an array of persons sorted according to whoever finishes taking money first.

**Example:**
Amounts = {5, 1, 2}
k = 2
Answer = {2, 3, 1}


---

### Manhattan Distance to Line Segments
We are given line segments in the XY plane that are always parallel to the X-axis or Y-axis.

Each line segment is defined as:
{x1, y1, x2, y2}


You are given a vector of vectors of this form.

We must find a point in the XY plane from which the **Manhattan distance** to all the line segments is minimized, where Manhattan distance is:

|x - x1| + |y - y1|

If two points give the minimum distance, return the one with the **smaller x-coordinate**.
