# Two Sum - DSA Problem

## 🧠 Problem
Given an array of integers and a target, return indices of two numbers such that they add up to target.

## 💡 Approach
Used HashMap to store visited elements.
For each element:
- Calculate complement (target - current)
- Check if complement exists in map
- If yes, return indices

## ⏱ Time Complexity
O(n)

## 📦 Space Complexity
O(n)
