# Solutions :octocat:
`C++` solutions for online algorithm problems from LeetCode and HackerRank.

<br />

## LeetCode
*Questions are listed with their corresponding titles and problem numbers from LeetCode*

1. -[X] **1.** [Add Two Numbers (in a linked list)](LeetCode/AddTwoNumbers.cpp) [2]

You are given two **non-empty** linked lists representing two non-negative integers. The digits are stored in reverse order and each of their nodes contain a single digit. Add the two numbers and return it as a linked list.

You may assume the two numbers do not contain any leading zero, except the number 0 itself.
```
Input: (2 -> 4 -> 3) + (5 -> 6 -> 4)
Output: 7 -> 0 -> 8
```

<br/>

2. -[X] **2.** [Climbing Stairs](LeetCode/ClimbingStairs.cpp) [70]

You are climbing a stair case. It takes n steps to reach to the top.

Each time you can either climb 1 or 2 steps. In how many distinct ways can you climb to the top?

**Note:** Given n will be a positive integer.

<br/>

3. -[X] **3.** [Container With Most Water](LeetCode/ContainerWithMostWater.cpp) [11]

Given n non-negative integers a1, a2, ..., an, where each represents a point at coordinate (i, ai). n vertical lines are drawn such that the two endpoints of line i is at (i, ai) and (i, 0). Find two lines, which together with x-axis forms a container, such that the container contains the most water.

Note: You may not slant the container and n is at least 2.

<br />

4. -[X] **4.** [First Missing Positive](LeetCode/FirstMissingPositive.cpp) [41]

Given an unsorted integer array, find the first missing positive integer.

For example, <br/>
Given `[1,2,0]` return `3`, <br/>
and `[3,4,-1,1]` return `2`.

Your algorithm should run in O(n) time and uses constant space.

<br/>

5. -[X] **5.** [Friend Circles](LeetCode/FriendCircles.cpp) [547]
 
There are N students in a class. Some of them are friends, while some are not. Their friendship is transitive in nature. For example, if A is a direct friend of B, and B is a direct friend of C, then A is an indirect friend of C. And we defined a friend circle is a group of students who are direct or indirect friends.
 
Given a N*N matrix M representing the friend relationship between students in the class. If M[i][j] = 1, then the ith and jth students are direct friends with each other, otherwise not. And you have to output the total number of friend circles among all the students.

Example 1:
 ```
 Input: 
  [[1,1,0],
   [1,1,0],
   [0,0,1]]
  Output: 2
  Explanation:The 0th and 1st students are direct friends, so they are in a friend circle. 
  The 2nd student himself is in a friend circle. So return 2.
  ```
Example 2:
  ```
Input: 
[[1,1,0],
 [1,1,1],
 [0,1,1]]
Output: 1
Explanation:The 0th and 1st students are direct friends, the 1st and 2nd students are direct friends, 
so the 0th and 2nd students are indirect friends. All of them are in the same friend circle, so return 1.
```
Note:
1. N is in range [1,200].
2. M[i][i] = 1 for all students.
3. If M[i][j] = 1, then M[j][i] = 1.

<br />

6. -[X] **6.** [Generate Parentheses](LeetCode/GenerateParentheses.cpp) [22]

Given *n* pairs of parentheses, write a function to generate all combinations of well-formed parentheses.

For example, given *n = 3*, a solution set is:
```
[
  "((()))",
  "(()())",
  "(())()",
  "()(())",
  "()()()"
]
```

<br />

7. -[X] **7.** [Palindrome Number](LeetCode/IntegerPalindrome.cpp) [9]

Determine whether an integer is a palindrome. Do this without extra space.

<br />

8. -[X] **8.** [Integer to Roman Numeral](LeetCode/IntegerToRomanNum.cpp) [12]

Given an integer, convert it to a roman numeral.
Input is guaranteed to be within the range from 1 to 3999.

<br />

9. -[X] **9.** [Is Subsequence](LeetCode/IsSubsequence.cpp) [392]

Given a string **s** and a string **t**, check if **s** is subsequence of **t**.

You may assume that there is only lower case English letters in both **s** and **t**. **t** is potentially a very long (length ~= 500,000) string, and **s** is a short string (<=100).
 
A subsequence of a string is a new string which is formed from the original string by deleting some (can be none) of the characters without disturbing the relative positions of the remaining characters. (ie, "ace" is a subsequence of "abcde" while "aec" is not).
 
**Example 1:**

s = "abc", t = "ahbgdc"
 
Return `true`.

**Example 2:**

s = "axc", t = "ahbgdc"

Return `false`.

<br />

10. -[X] **10.** [Jump Game](LeetCode/JumpGame.cpp) [55]

Given an array of non-negative integers, you are initially positioned at the first index of the array.

Each element in the array represents your maximum jump length at that position.

Determine if you are able to reach the last index.

For example: <br/>
A = `[2,3,1,1,4]`, return `true`.

A = `[3,2,1,0,4]`, return `false`.

<br/>

11. -[ ] **11.** [Longest Substring Without Repeating Characters](LeetCode/LengthofLongestSubstring.cpp) [3]

Given a string, find the length of the longest substring without repeating characters.
 
Examples:

Given "abcabcbb", the answer is "abc", which the length is 3.

Given "bbbbb", the answer is "b", with the length of 1.

Given "pwwkew", the answer is "wke", with the length of 3. Note that the answer must be a substring, "pwke" is a subsequence and not a substring.

<br />

12. -[X] **12.** [Letter Combinations of a Phone Number](LeetCode/LetterCombosofPhoneNum.cpp) [17]

Given a digit string, return all possible letter combinations that the number could represent.

```
Input:Digit string "23"
Output: ["ad", "ae", "af", "bd", "be", "bf", "cd", "ce", "cf"].
```

<br />

13. -[X] **13.** [Longest Common Prefix](LeetCode/LongestCommonPrefixString.cpp) [14]

Write a function to find the longest common prefix string amongst an array of strings.

<br />

14. -[X] **14.** [Longest Continuous Increasing Subsequence](LeetCode/LongestContIncSubsequence.cpp) [674]

Given an unsorted array of integers, find the length of longest **continuous** increasing subsequence.

**Example 1:**
```
Input: [1,3,5,4,7]
Output: 3
Explanation: The longest continuous increasing subsequence is [1,3,5], its length is 3. 
Even though [1,3,5,7] is also an increasing subsequence, it's not a continuous one where 5 and 7 are separated by 4. 
```

**Example 2:**
```
Input: [2,2,2,2,2]
Output: 1
Explanation: The longest continuous increasing subsequence is [2], its length is 1. 
```

**Note:** Length of the array will not exceed 10,000.

<br/>

15. -[X] **15.** [Longest Increasing Subsequence](LeetCode/LongestIncSubsequence.cpp) [300]

Given an unsorted array of integers, find the length of longest increasing subsequence.

For example, <br/>
Given `[10, 9, 2, 5, 3, 7, 101, 18]`,
The longest increasing subsequence is `[2, 3, 7, 101]`, therefore the length is `4`. Note that there may be more than one LIS combination, it is only necessary for you to return the length.

Your algorithm should run in O(n2) complexity.

**Follow up:** Could you improve it to O(n log n) time complexity?

16. -[X] **16.** [Longest Univalue Path](LeetCode/LongestUnivaluePath.cpp) [687]

Given a binary tree, find the length of the longest path where each node in the path has the same value. This path may or may not pass through the root.

Note: The length of path between two nodes is represented by the number of edges between them.

**Example 1:**

Input:
```
              5
             / \
            4   5
           / \   \
          1   1   5
```

Output: 
```
2
```
**Example 2:**

Input:
```
              1
             / \
            4   5
           / \   \
          4   4   5
```
Output:
```
2
```

<br />

17. -[X] **17.** [Median of Two Sorted Arrays](LeetCode/MedianSortedArrays.cpp) [4]

There are two sorted arrays nums1 and nums2 of size m and n respectively.

Find the median of the two sorted arrays. The overall run time complexity should be O(log (m+n)).

**Example 1:**
```
nums1 = [1, 3]
nums2 = [2]

The median is 2.0
```

**Example 2:**
```
nums1 = [1, 2]
nums2 = [3, 4]

The median is (2 + 3)/2 = 2.5
```

<br />

18. -[X] **18.** [Merge Two Sorted Lists](LeetCode/MergeTwoSortedLists.cpp) [21]

Merge two sorted linked lists and return it as a new list. The new list should be made by splicing together the nodes of the first two lists.

<br />

19. -[X] **19.** [Find Minimum in Rotated Sorted Array II](LeetCode/MinRotatedSortedArr.cpp) [154]

Suppose an array sorted in ascending order is rotated at some pivot unknown to you beforehand.

(i.e., 0 1 2 4 5 6 7 might become 4 5 6 7 0 1 2).

Find the minimum element.

The array may contain duplicates.

<br />


20. -[X] **20.** [Move Zeroes](LeetCode/MoveZeroes.cpp) [283]

Given an array `nums`, write a function to move all 0's to the end of it while maintaining the relative order of the non-zero elements.

For example, given `nums = [0, 1, 0, 3, 12]`, after calling your function, nums should be `[1, 3, 12, 0, 0]`.

Note:
You must do this in-place without making a copy of the array. <br/>
Minimize the total number of operations.

<br/>


21. -[X] **21.** [Multiply Strings](LeetCode/MultiplyStrings.cpp) [43]

Given two non-negative integers `num1` and `num2` represented as strings, return the product of `num1` and `num2`.

**Note:**

1. The length of both `num1` and `num2` is < 110. <br/>
2. Both `num1` and `num2` contains only digits `0-9`.<br/>
3. Both `num1` and `num2` does not contain any leading zero. <br/>
4. You must not use any built-in BigInteger library or convert the inputs to integer directly. <br/>

<br/>

22. -[X] **22.** [Palindrome Linked List](LeetCode/PalindromeLinkedList.cpp) [234]

Given a singly linked list, determine if it is a palindrome.

<br />

23. -[X] **23.**  [Pascal's Triangle](LeetCode/PascalsTriangle.cpp) [118]

Given numRows, generate the first numRows of Pascal's triangle.

For example, given numRows = 5,

Return:
```
[
     [1],
    [1,1],
   [1,2,1],
  [1,3,3,1],
 [1,4,6,4,1]
]
```

<br />

24. -[X] **24.** [Permutations in a String](LeetCode/PermutationsInAString.cpp) [567]

Given two strings **s1** and **s2**, write a function to return true if **s2** contains the permutation of **s1**. In other words, one of the first string's permutations is the **substring** of the second string.

**Example 1:**
```
Input: s1 = "ab" s2 = "eidbaooo"
Output: True
```
Explanation: s2 contains one permutation of s1 ("ba").

**Example 2:**
```
Input:s1= "ab" s2 = "eidboaoo"
Output: False
```

**Note:**
The input strings only contain lower case letters.
The length of both given strings is in range [1, 10,000].

<br/>

25. -[X] **25.** [Plus One](LeetCode/PlusOne.cpp) [66]

Given a non-negative integer represented as a **non-empty** array of digits, plus one to the integer.

You may assume the integer do not contain any leading zero, except the number 0 itself.

The digits are stored such that the most significant digit is at the head of the list.

<br />

26. -[X] **26.** [Pow(x, n)](LeetCode/Power.cpp) [50] 

Implement `pow(x, n)`.

<br />

27. -[X] **27.** [Power of Four](LeetCode/PowerOfFour.cpp) [342]

Given an integer (signed 32 bits), write a function to check whether it is a power of 4.

**Example:**

Given num = 16, return true. Given num = 5, return false.

Follow up: Could you solve it without loops/recursion?

<br />

28. -[X] **28.** [Removed Duplicates From Sorted Array](LeetCode/RemoveDupSortedArr.cpp) [26]

Given a sorted array, remove the duplicates in-place such that each element appear only once and return the new length.

Do not allocate extra space for another array, you must do this by modifying the input array in-place with O(1) extra memory.

**Example:**
```
Given nums = [1,1,2],

Your function should return length = 2, with the first two elements of nums being 1 and 2 respectively.
It doesn't matter what you leave beyond the new length.
```

<br/>

29. -[X] **29.** [Remove Nth Node From End of List](LeetCode/RemoveNthFromEndLinkedList.cpp) [19]

Given a linked list, remove the nth node from the end of list and return its head.

For example,
```
   Given linked list: 1->2->3->4->5, and n = 2.

   After removing the second node from the end, the linked list becomes 1->2->3->5.
   ```
**Note:**

Given n will always be valid.
Try to do this in one pass.

<br />

30. -[X] **30.** [Reverse Integer](LeetCode/ReverseInteger.cpp) [7]

Reverse digits of an integer.

Example1: x = 123, return 321

Example2: x = -123, return -321

<br />

31. -[X] **31.** [Searchfor a Range](LeetCode/SearchForRange.cpp) [34]

Given an array of integers sorted in ascending order, find the starting and ending position of a given target value.

Your algorithm's runtime complexity must be in the order of *O(log n)*.

If the target is not found in the array, return `[-1, -1]`.

For example, <br/>
Given `[5, 7, 7, 8, 8, 10]` and target value 8,
return `[3, 4]`.

<br/>

32. -[X] **32.** [Set Matrix Zeroes](LeetCode/SetMatrixZeroes.cpp) [73]

Given a m x n matrix, if an element is 0, set its entire row and column to 0. Do it in place.

<br/>

33. -[X] **33.** [Subsets](LeetCode/Subsets.cpp) [78]

Given a set of **distinct** integers, nums, return all possible subsets (the power set).

**Note:** The solution set must not contain duplicate subsets.

For example, <br/>
If ***nums*** = `[1,2,3]`, a solution is:
```
[
  [3],
  [1],
  [2],
  [1,2,3],
  [1,3],
  [2,3],
  [1,2],
  []
]
```

<br/>

34. -[ ] **34.** [Third Maximum Number](LeetCode/ThirdMax.cpp) [414]

Given a non-empty array of integers, return the third maximum number in this array. If it does not exist, return the maximum number. The time complexity must be in O(n).

Example 1:
Input: [3, 2, 1]

Output: 1

Explanation: The third maximum is 1.

Example 2:
Input: [1, 2]

Output: 2

Explanation: The third maximum does not exist, so the maximum (2) is returned instead.

Example 3:
Input: [2, 2, 3, 1]

Output: 1

Explanation: Note that the third maximum here means the third maximum distinct number.
Both numbers with value 2 are both considered as second maximum.

<br />

35. -[X] **35.** [3Sum](LeetCode/ThreeSum.cpp) [15]

Given an array S of n integers, are there elements a, b, c in S such that a + b + c = 0? Find all unique triplets in the array which gives the sum of zero.

Note: The solution set must not contain duplicate triplets.

For example, given array S = [-1, 0, 1, 2, -1, -4],

A solution set is:
[
  [-1, 0, 1],
  [-1, -1, 2]
]

<br />

36. -[X] **36.** [3Sum Closest](LeetCode/ThreeSumClosest.cpp) [16]

Given an array S of n integers, find three integers in S such that the sum is closest to a given number, target. Return the sum of the three integers. You may assume that each input would have exactly one solution.

```
For example, given array S = {-1 2 1 -4}, and target = 1.

The sum that is closest to the target is 2. (-1 + 2 + 1 = 2).
```

<br />

37. -[X] **37.** [Validate Binary Search Tree](LeetCode/ValidBST.cpp) [98]

Given a binary tree, determine if it is a valid binary search tree (BST).

Assume a BST is defined as follows:

* The left subtree of a node contains only nodes with keys less than the node's key.
* The right subtree of a node contains only nodes with keys greater than the node's key.
* Both the left and right subtrees must also be binary search trees.

**Example 1:**
```
    2
   / \
  1   3
  ```
  Binary tree `[2,1,3]`, return true.
  
**Example 2:**
```
    1
   / \
  2   3
```
Binary tree `[1,2,3]`, return false.

<br />

38. -[X] **38.** [Valid Parentheses](LeetCode/ValidParentheses.cpp) [20]

Given a string containing just the characters `'('`, `')'`, `'{'`, `'}'`, `'['` and `']'`, determine if the input string is valid.

The brackets must close in the correct order, `"()"` and `"()[]{}"` are all valid but `"(]"` and `"([)]"` are not.

<br />

39. -[X] **39.** [Word Search](LeetCode/WordSearch.cpp) [79]

Given a 2D board and a word, find if the word exists in the grid.

The word can be constructed from letters of sequentially adjacent cell, where "adjacent" cells are those horizontally or vertically neighboring. The same letter cell may not be used more than once.

For example,

Given board =

```
[
  ['A','B','C','E'],
  ['S','F','C','S'],
  ['A','D','E','E']
]
```

word = `"ABCCED"`, -> returns `true`, <br/>
word = `"SEE"`, -> returns `true`, <br/>
word = `"ABCB"`, -> returns `false`.

40. -[X] **40.** [ZigZag Conversion](LeetCode/ZigZagConversion.cpp) [6]

The string `"PAYPALISHIRING"` is written in a zigzag pattern on a given number of rows like this: (you may want to display this pattern in a fixed font for better legibility)

```
P   A   H   N
A P L S I I G
Y   I   R
```
And then read line by line: `"PAHNAPLSIIGYIR"`
Write the code that will take a string and make this conversion given a number of rows:
```C++
string convert(string text, int nRows);
```
`convert("PAYPALISHIRING", 3)` should return `"PAHNAPLSIIGYIR"`.

<br />

## Hacker Rank
1. -[X] **1.** [Apple and Orange](HackerRank/AppleAndOrangeTrees.cpp)

<br />

## Other
1. -[ ] **1.** [Islands](Other/Island.cpp)
2. -[ ] **2.** [Twitter](Other/Twitter.cpp)


