# Graviton

Test – 1 hour each

---

## Quant - Test

### 1. Even White Tiles on an 8×8 Board
You have an 8×8 board. You need to fill it with 64 tiles such that the number of white tiles in **each row and each column is even**.

---

### 2. Permutations with Difference 1 Condition
How many permutations of the numbers `{1, 2, 3, ..., 9}` are possible such that **each number (except the first one)** has **some number before it whose difference with it is 1**?

---

### 3. Alice–Bob Number Picking Game
Alice and Bob take turns choosing numbers from the set `{2, 3, ..., 30}`.

The first person to pick a number which has a **common factor** with **any number already picked** loses.

Alice can choose to start **first or second**.

Determine:
- How Alice should start
- What her strategy should be

---

### 4. Markov Chains
A Markov chain with:
- 6 states
- 3 different connection ways

Find the **stationary distribution** for each case.

---

## Software - Test

### 1. Minimum Cost Path in a Tree with Discounts
You are given:
- A tree with edges of the form `edges[i] = [ai, bi]`
- Queries of the form `[source, destination]`
- An array `prices[i]` for each node

When traversing a node, `prices[i]` is added to the cost.

Before starting traversal, you can **halve the prices of some non-adjacent nodes**.

Find the **minimum cost path** for all queries and give the **algorithm**.

---

### 2. Subarray Minimum Operations
You are given an array of size `n` and an integer `k ≤ n`.

In one operation:
- Choose a subarray of size `k`
- Compute the minimum value in that subarray

After performing `Q` operations, find the minimum possible value of:

`(maximum of operation results − minimum of operation results)`

---

### 3. Multi-Stage Instruction Execution
Given multiple stages of an instruction 
- Find the time taken to execute a program of 100 instructions if the processor is single cycle and if it is multi cycle 
- Mention pipeline hazards what Instruction sequence can cause them and how to detect and resolve 
- Cache hierarchy question

---

### 4. Something related to mmap and brk syscalls