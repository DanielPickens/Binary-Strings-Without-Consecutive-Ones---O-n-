# Binary-Strings-Without-Consecutive-Ones---O-n-
An algorithm and my solution


The Algo: 
Given a non-negative integer N return the number of binary strings of length N without 2 consecutive ones

Example:

Input: N = 3
Output: 5
Explanation: [
    "000",
    "001",
    "010",
    "100",
    "101",

Notes: N <= 30



Steps taken to solve this: 

 Step # 1 / 5
Declared an array of integers named dp of length n + 1
 
 Step # 2 / 5
Initialized the function of dp[0] and dp[1] to be associated  with 1 and 2 respectively
 
 Step # 3 / 5
Using an index i, iterated over the indices of dp starting at index 2
 
 Step # 4 / 5
Computed dp[i] by adding up dp[i - 1] and dp[i - 2]
 
 Step # 5 / 5
Finally, returned dp[n]


Time Complexity: O(n)
