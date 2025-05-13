# Day14-50-days-coding-challenge
This repository contains solutions for **Day 14** of my #DrGViswanathanChallenge.  
Today’s focus was on two algorithmic problems involving:

## 🔁 Problem 1: Reverse Integer
**Problem:** Given a signed 32-bit integer `x`, reverse the digits. If the reversed number overflows the signed 32-bit range, return 0.  
**Constraints:** No usage of 64-bit integers (signed or unsigned).

### ✅ Example:
- Input: `x = 123` → Output: `321`
- Input: `x = -123` → Output: `-321`
- Input: `x = 120` → Output: `21`

### 🧠 Approach:
- Extract digits using modulo and division.
- Check overflow before pushing to the result.

## 🔁 Problem 2: Partition List
**Problem:** Given the head of a linked list and a value `x`, partition it such that all nodes less than `x` come before nodes greater than or equal to `x`.  
**Constraints:** Maintain relative order of nodes in both partitions.

### ✅ Example:
- Input: `head = [1,4,3,2,5,2], x = 3` → Output: `[1,2,2,4,3,5]`
- Input: `head = [2,1], x = 2` → Output: `[1,2]`

### 🧠 Approach:
- Use two dummy nodes for "before" and "after" lists.
- Traverse and categorize, then reconnect both lists.
