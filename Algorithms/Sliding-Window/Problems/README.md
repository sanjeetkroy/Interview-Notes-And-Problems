# Some Sliding Window Problems
1. __Maximum sum subarray of Size k__
   
Given an array of positive integers, and a positive number k, find the maximum sum of any contiguous subarray of size k.
```
Input: [3, 5, 2, 1, 7], k=2
Output: 8
```  

__Explanation__
```
Here the subarray [1, 7] or [3, 5] is the sum of the maximum sum.
```
- - - -
2.  __Count Occurrences of Anagram__
    
Given a word and a text, return the count of occurrences of the anagrams of the word in the text.
> Anagram is a word, phrase, or sentence formed from another by rearranging its letters. 
> Example: `race` is anagrams of `care`
```
Input: text = gotxxotgxdogt, word = got
Output : 3
```  

__Explanation__
```
Words — got, otg, ogt are anagrams of got.
```
- - - -
3. __Difference between the maximum and minimum average of all k-length continuous subarrays__

```
Input: arr[ ] = {3, 8, 9, 15}, K = 2
Output: 6.5
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
4. __Find the longest substring of a string containing ‘k’ distinct characters__

```
Input: s = 'abcbdbdbbdcdabd'
k = 2
Output: bdbdbbd
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -

5. __Find duplicates within a range ‘k’ in an array__

```
Input: nums = [5, 6, 8, 2, 4, 6, 9]
k = 2
Ouput: False
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -

6. __Find minimum Sum SubArray of size k__

```
Input: arr = [10, 4, 2, 5, 6, 3, 8, 1]
k = 3
Output: 11
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -

7. __Length of the longest substring that doesn’t contain any vowels__

```
Input: s = "codeforintelligents"
Output: 3
Explanation: 'nts' is the longest substring that doesn't contain any vowels.
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
8. __Count negative elements present in every k-length subarray__
```
Input: arr = [-1, 2, -2, 3, 5, -7, -5], K = 3
Output: 2, 1, 1, 1, 2
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
9. Minimum Size Subarray Sum
```
Input: target = 7, nums = [2,3,1,2,4,3]
Output: 2
Explanation: The subarray [4,3] has the minimal length under the problem constraint
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
10. __Longest Repeating Character Replacement__

You are given a string s and an integer k. You can choose any character of the string and change it to any other uppercase English character. You can perform this operation at most k times.

```
Input: s = "ABAB", k = 2
Output: 4
Explanation: Replace the two 'A's with two 'B's or vice versa.
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
11. __Count distinct absolute values in a sorted array__

```
Input:  { -1, -1, 0, 1, 1, 1 }
Output: The total number of distinct absolute values is 2 (0 and 1)
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
12. __Permutation in String__

Given two strings s1 and s2, return true if s2 contains a permutation of s1, or false otherwise.

In other words, return true if one of s1’s permutations is the substring of s2.
```
Input: s1 = "ab", s2 = "eidbaooo"
Output: true
Explanation: s2 contains one permutation of s1 ("ba").
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
13. __Find All Anagrams in a String__
```
Input: s = "cbaebabacd", p = "abc"
Output: [0,6]
Explanation:
The substring with start index = 0 is "cba", which is an anagram of "abc".
The substring with start index = 6 is "bac", which is an anagram of "abc".
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -
14. __Maximum Average Subarray I__

You are given an integer array of nums consisting of n elements, and an integer k.

Find a contiguous subarray whose length is equal to k that has the maximum average value and return this value. Any answer with a calculation error less than 10–5 will be accepted.
```
Input: nums = [1,12,-5,-6,50,3], k = 4
Output: 12.75000
Explanation: Maximum average is (12 - 5 - 6 + 50) / 4 = 51 / 4 = 12.75
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -