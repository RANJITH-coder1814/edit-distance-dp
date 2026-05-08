📏 Edit Distance (LeetCode 72)

🧩 Problem Statement

Given two strings word1 and word2, return the minimum number of operations required to convert word1 into word2.

Allowed Operations:
Insert a character
Delete a character
Replace a character
💡 Approach (Dynamic Programming)

We use a 2D DP table where:

dp[i][j] = minimum operation
