# Leetcode_Day55
# Day 55 – Palindrome Linked List

## 🧩 Problem
**LeetCode 234 – Palindrome Linked List**

Given the head of a singly linked list, determine whether the linked list is a palindrome.

A palindrome reads the same from left to right and right to left.

### Example
Input: `1 → 2 → 2 → 1`  
Output: `true`

Input: `1 → 2`  
Output: `false`

---

## 💡 Approach

I used the **Slow and Fast Pointer** technique to find the middle of the linked list.

### Steps:
1. Use `slow` and `fast` pointers to find the middle node.
2. Reverse the second half of the linked list.
3. Compare the first half with the reversed second half.
4. If all corresponding values are equal, the list is a palindrome.

The key idea is to avoid using extra space for storing all the values.

---

## 🧠 What I Learned

Today I learned how **slow and fast pointers** can help divide a linked list into two parts.

I also practiced **reversing a linked list**, which is an important technique that appears in many linked-list problems.

Instead of always trying to store everything in an array, we can sometimes solve the problem by changing how we traverse the data.

---

## ⏱️ Complexity

- **Time Complexity:** `O(n)`
- **Space Complexity:** `O(1)`

---

## 🎯 Takeaway

Today's problem reminded me that a problem can become much simpler when I stop looking at the entire data at once and break it into smaller parts.

**Day 55 complete — another small step forward in my DSA journey.**
