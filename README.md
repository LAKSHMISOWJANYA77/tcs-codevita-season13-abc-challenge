# ABC Challenge - TCS CodeVita Season 13

## Overview

This repository contains my accepted Java solution for the **ABC Challenge** problem solved during **TCS CodeVita Season 13 Round 1**.

## Problem Summary

Items belonging to three owners (A, B, and C) are arranged in a sequence. The goal is to group all items of the same owner together while preserving ownership at certain fixed positions.

The task is to determine the minimum number of shift operations required, or report that no valid arrangement exists.

## Approach

1. Count occurrences of A, B, and C.
2. Generate all six possible grouped orders.
3. Construct the target arrangement for each order.
4. Verify the fixed-position constraints.
5. Use Longest Common Subsequence (LCS) to compute the minimum number of shift operations.

Minimum Shifts = N − LCS(original, target)

6. Return the minimum valid answer among all feasible arrangements.

## Complexity

* Time Complexity: O(6 × N²)
* Space Complexity: O(N²)

## Technologies Used

* Java
* Dynamic Programming
* Longest Common Subsequence (LCS)
* Permutation Generation

## Result

Accepted solution submitted during TCS CodeVita Season 13 Round 1.

